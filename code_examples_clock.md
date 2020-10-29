That is application which draws clock face based on CoreGraphics api. Sources here:

https://github.com/fizzy871/FSClock



#### Screenshots of code

###### CALayer subclass to draw clock hand. Uses UIBezierPath

![](code_examples_img/hand.png)

-------

###### CALayer subclass to draw clock face. Do not use UIBezierPath

![](code_examples_img/face.png)

------

###### Code where time updates. Triggered by CADisplayLink, 24 frames per second.

![](code_examples_img/time.png)

-----

###### Final result

![](code_examples_img/clock_app.png)
