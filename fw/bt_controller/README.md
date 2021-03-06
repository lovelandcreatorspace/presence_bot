### btle_control

Control the arduino remotely using (quasi) serial over bluetooth LE.

The bluetooth module being used is the BLE Mini from RedBearLab - documentation and example code is available at [http://redbearlab.com/blemini/](http://redbearlab.com/blemini/). Follow instructions for downloading and installing the RBL BLEMini libraries and example code.

We are using the ardumoto shield from sparkfun to interface with the motors -documentation and code are available at [https://www.sparkfun.com/products/9815](https://www.sparkfun.com/products/9815). 

Quick tips when using the standard BLE Controller app for android: 

	* Each motor is controlled by two pins -
		* one digital pin to set the direction
		* one PWM pin to set the speed
	* Motor outputs 1/2 are controlled by
		* pin 12 (digital out, controls direction)
		* pin 3  (PWM out, controls speed)
	* Motor outputs 1/2 are controlled by
		* pin 13 (digital out, controls direction)
		* pin 11 (PWM out, controls speed)

