# Processing Code

This is the Processing library. It has a [Firmata](http://firmata.org) dependency, so you will need to install the [processing lib](https://github.com/pardo-bsso/processing-arduino), and also install the Firmata firmware on your arduino (in arduino IDE: File -> Open -> Examples > Library-Firmata > StandardFirmata.)

Once you have done these 2 things, put the processing/libraries/arduinoscope folder in your processing libraries folder (on mac: `~/Documents/Processing/libraries`.)

Now, restart processing, and you should have an arduinoscope example (under File/Examples.) This is the source for the stand-alone apps.

 ****** Modified by Sean Montgomery (www.ProduceConsumeRobot.com) 2013/04 *******
 * https://github.com/produceconsumerobot/
 * 
 * - Bug fix: Changed line drawing from line(x, y1, x, y2) to line(x1, y1, x2, y2) to
 *		avoid problem in Processing 2.0b8 that draws nothing if calling line(x, y, x, y)
 *
 * - New Feature: Added public void setPointsPerWindow(int nPoints) so that the amount
 * 		(time window) of data displayed on the screen can be easily changed.
 * 
 */