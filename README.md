# happy-music-hacking
Programming with an esoteric programming language [ORCA](https://github.com/hundredrabbits/Orca),
as MIDI event generator, resulting in a programmatic approach to music :)

AND IT'S FUN!!! :D:D:D

Happy hacking!

Example:

![example](22-12-2019-Techno/example.gif)

## ORCA overview

ORCA is an esoteric programming language as stated by the inventors [hundredrabbits](http://100r.co).

Basically it's all about generating events, so called bangs.
These take place within a certain frame and can generate MIDI or other events, like UDP Messages.
Due to this design, ORCA can be used for many things like programming music or visual components.

As a part of house of mints art project this will be a big part, since the structure and shire amounts
of possibilities allow unlimited creativity (Once one got started). ORCA works in a free space,
unlike programming laguages usually do.

For the first session see **22-12-2019-Techno** where we created a few patterns that nicly illustrate
how ORCA works.


## Working with ORCA

In order to make music with ORCA, one needs to have some sort of sound source, that can work with the
generated MIDI/UDP events. For getting started I recommend using [Pilot](https://github.com/hundredrabbits/pilot),
but there are several other companion applications:

- [Estra](https://github.com/kyleaedwards/estra), a companion sampler tool.
- [Gull](https://github.com/qleonetti/gull), a companion sampler, slicer and synth tool.
- [Sonic Pi](https://in-thread.sonic-pi.net/t/using-orca-to-control-sonic-pi-with-osc/2381/), a livecoding environment.

If you have worked with Ableton live before, this is a very powerfull (but also expensive (very expensive)) option.
Only recommanded if you'r really ambitious about this kind of stuff.



## Orca cheatsheet

When your getting started, this cheatsheet should help a lot. A function for every letter in the alphabet
can be a little overwhelming at time.

	a Outputs sum of inputs
	b Outputs difference between inputs
	c Outputs modulo of frame
	d Bangs on modulo of frame
	e Moves eastward, or bangs
	f Bangs if inputs are equal
	g Writes operands with offset
	h Halts southward operands
	i Increments southwards operands
	j Increments northwards operands
	k Reads multiple variables
	l Outputs the smallest input
	m Outputs product of inputs
	n Moves northward, or bangs
	o Read operand with offset
	p Writes eastward operand
	q Reads operands with offset
	r Outputs random value
	s Moves southwards, or bangs
	t Reads eastward operand
	u angs on Euclidean rhythm
	v Reads and writes variable
	w Modes westward, or bangs
	x Writes operand with offset
	y Outputs westward operand
	z Transitions operand to target
	* bangs neighboring operands
	# Halts line
	$ Sends ORCA command
	: Sends MIDI note
	! Sends MIDI control change
	? Sends MIDI oitch bend
	% Sends MIDI monophonic note
	= Sends OSC message
	; Sends UDP message

