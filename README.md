PROPTB6612FNG a simple library to use the Thosiba TB6612FNG dual motor controller on the Parallax Propeller
sw@kaltpost.de
http://gpio.kaltpost.de/


Introduction
------------

PROPTB6612FNG  is a simple library to use the Thosiba TB6612FNG dual motor controller on the
Parallax Propeller.

The driver offers methods to operate each motor individually or both motors together (by sending the
same command to each, or sending a different command to each).

It optinally allows to adjust the speed for each motor in %. The Speed adjustment is done through the
TB6612FNG PWM input. For each motor (A or B) speedcontrol through PWM is used, a Cog is reserved to
generate the PWM.


Usage
-----

PROPTB6612FNG is written in SPIN. Thus, a spin compiler is needed. If unsure how to get the toolchain,
have a look [here](http://gpio.kaltpost.de/?page_id=1378).

To demonstrate the usage, a examples is provided:

* ``SimpleExample``: shows the basic usage of the library

