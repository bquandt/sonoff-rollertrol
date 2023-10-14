# sonoff-rollertrol
## Simple H-bridge circuit using a Sonoff 4ch pro device to control 12V 2wire motors.   
### To use (wire it up as shown) then create two scenes 

1.  "shades up" -- turns all switches off, then turns A,B on
1.  "shades down" -- turns all switches off, then turns C,D on

### DO NOT trigger other combinations together, some will short out (use this diagram at your own discretion).

![alt text](https://github.com/bquandt/sonoff-rollertrol/blob/main/sonoff-h-bridge.png "Sonoff H-Bridge")

### This was a no-thrills no firmware mods required way to do things.   Might even be a way to do this with less relays, let me know if there is.
