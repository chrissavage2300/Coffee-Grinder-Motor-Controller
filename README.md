# Coffee-Grinder-Motor-Controller

This is just a simple project where I retrofitted a hand crank grinder with a powerful gear motor.

Motor Used: https://www.servocity.com/118-rpm-hd-premium-planetary-gear-motor

Angle Bracket: https://www.servocity.com/90-single-angle-short-channel-bracket

Mount: https://www.servocity.com/hd-premium-planetary-gear-motor-mount-face-thru-hole

The software works as follows: Ramps up within a second or two from 25% to 100% full speed and then counts when the current goes below a minimum value. Once the current goes below that value, it shuts the motor off and waits for the user to press a button again. I had to measure the current using debugging and then average it out in excel to find a minimum value for when the coffee is ground.  During grinding the current is mostly higher than this min, so it wont trigger, but when the grinder is idling, it will hit that minumum more often. 


