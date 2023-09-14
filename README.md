# file_source

SDR++ file source with rewind/forward buttons and time passed.

I like recording long and huge IQ files using SDR++, but I don't like to sit by them the same time they elapsed. Also,
I don't like when some signal passed, but I couldn't check it without replaying from the beginning. I think every file
player must have rewind/forward buttons.

And the player is also useless without display of total length and playing time.

I added rewind/forward by 5, 10 and 30 seconds and 5, 10 and 30 minutes. If you'd like to use this functionality, simply
replace `file_source` source with this repository and recompile SDR++.

So buttons and time is the minimum I need for myself to work with long IQ files. Here's an example screenshot:

!["File Source with rewind/forward and elapsed/total time"](screenshots/rewind-forward-time.png?raw=true)

[There's a discussion over file playing functionality on SDRPlusPlus board](https://github.com/AlexandreRouma/SDRPlusPlus/issues/129).
Hopefully, it will be implemented in a better way some time later.
