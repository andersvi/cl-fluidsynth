# cl-fluidsynth - Common Lisp interface to (lib)fluidsynth #

This library provides ffi-bindings to launch and control
[FluidSynth](http://www.fluidsynth.org/) from Lisp.

Originally programmed as part of the Linux port of OpenMusic in 2013.
Later extracted into a self-contained package.

The file [test-1.lisp](file:test-1.lisp) contains some testing code, most of these
depend on cl-jack being available and set up.

As of 2014 I'm aware of another library called cl-fluidsynth, part of
Tito Latini's [incudine](http://incudine.sourceforge.net/) programming
environment.  However, our version of cl-fluidsynth here has been used
in building applications since 2013 (most notably [OpenMusic6](https://github.com/openmusic-project/OM6)), and I'd rather not
change the name now.

Please send feedback if this kludges up things for you.

### Dependencies ###

`libfluidsynth`

##### *Anders Vinjar, 2013* #####


