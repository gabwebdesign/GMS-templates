GMS-templates
=============

Implementations the Greensock.com library on create templates to Advertisement banners.

----

Hi, this is a single solutions to create a templates banners using a greensocks library.

The firts case we are working on Actions Script, at the moment on AS2, then will work on AS3, Javascript, etc, adding the techology needed.

----

First of all, move the source code files Greensock and the owner file named MotionEventManager.as. When this done, import since the .fla files.


-----

import com.MotionEventManager;

/* initializing the class to events */
var _tl:MotionEventManager = new MotionEventManager();

/* global values */
var _frameTime:Number = 3;
var _duration:Number = 0.5;


/* init */
firstFrame(_frameTime);


function firstFrame():Void{
	
	/* Param 1: type of animation, Param 2: target   */
	_tl.init("fadeInStop", logo)
	
	
	/*  this timer controls the seconds to keep in the banner */

	_tl.setTimer(_frameTime)
	
}

------


