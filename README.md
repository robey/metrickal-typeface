
Metrickal
=========

Metrickal is an experimental geometric monospace typeface, created from
scratch, and intended for code editing and terminals (shell sessions).

It was designed on a retina display, for retina displays, so it has no
hinting and may look bad at chunkier resolutions, or with less-capable type
renderers.

The style is intended to mimic what a draftsman's handwriting might look
like: Simple but not cartoonish. Sans-serif, with a few exceptions to make
the monospace kerning less harsh. Easy to read at smaller point sizes.

By "experimental", I mean that I've never made a typeface from scratch
before, so this will probably take a while to look polished, and may never.

By "geometric", I mean that symmetry and math were emphasized first. When I
wanted to make a stroke at a 30 degree angle, I calculated where the points
should end up, and put them there. If a glyph looked weird, I would sketch it
out until I liked it, then go back to the drawing board and try to find lines
and curves that followed simple geometric principles and achieved the same
effect. That probably sounds pretentious, but another way to say it is: I
didn't trust my hand to draw any letters freeform.

<img src="https://raw.github.com/robey/metrickal-typeface/master/example.png">


Coverage
--------

Currently only ASCII is covered. The range of "unicode snowman" zones looked
daunting. But I'm open to filling them in.


License
-------

This typeface is licensed under the Apache 2 License. To avoid confusion,
please don't publish your own binary font files for public use under the
name "Metrickal" -- come up with your own name, or send me a pull request.


Code
----

There's no code. Instead, the typeface has been designed in "Glyphs Mini", a
great OS X app that you can find here:

    http://glyphsapp.com/

I've committed checkpoints so you can go back and see how bad things used to
look when it started, and so that (hopefully) future changes will be easier
to graphically diff.


Notes
-----

- height: 700
- x-height: 500
- width: 420
- left and right margins: 70 each
- baseline: -180
- punctuation overshoot (top & bottom): 80 each
- stroke thickness: 80
- ascender height: 800
- descender height: 200
- total width: 520 (1000x520)


Support
-------

If you need support for a typeface, you might be way out of your depth, but
if you want to talk about it, my email is:

    robeypointer@gmail.com

