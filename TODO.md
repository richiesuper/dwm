# TODOs for DWM

Things I want to do for dwm

## Bugs / bad things that needs to be fixed

- Fix dwm increase master windows function (known as incnmaster (.i = +1) in config.h) behavior

	I noticed that when repeatedly hitting the keybind for incnmaster (.i = +1), the "counter" of the master windows keeps
	increasing beyond the actual available windows. So, imagine I have 2 windows on tag 1, and the master windows count
	is originally 1. Then, I keep hitting the incnmaster (.i = +1) keybind and the count goes up beyond 2. To restore the
	master window count, I need to hit the reverse incnmaster (.i = -1) keybind to get it back to its original value.
	The reverse incnmaster (.i = -1) function works as expected though. It won't ever go beyond 0 (can't be lower than 0).
