#Leap Motion Controlled Sphero

A teacher at my son's school allowed me to use his Leap Motion over the weekend, I hacked together this quick and
dirty script to control Sphero using it.

See it in action: <http://www.youtube.com/watch?v=3ratT1yCnow&feature=share&list=UUKZdVrHYWr7rVNKbs9_fXnw>

Enjoy!

##Controls

* Rotate finger to set base heading (it only rotates clockwise)
* Push forward to make Sphero go straight ahead (heading of 0°)
* Pull backward to make Sphero go backward (heading of 180°)
* Swipe left to make Sphero go left (heading of 270°)
* Swipe right to make Sphero go right (heading of 90°)
* Swipe UP or DOWN to stop

##Install


##Notes

* Set `device` variable to whatever device Sphero connects to your machine has
* It's currently oversensitive so multiple gestures might get triggered and result in some wild behaviour!
* There is a timeout of 2000ms to stop Sphero after each gesture to make sure it doesn't go to crazy
* Comment out the contents of the timeout code if you are trying it out in water, it's much more fun and Sphero is
a bit more mellow when in liquid

