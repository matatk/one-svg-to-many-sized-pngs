One SVG to many sized PNGs
==========================

This takes one SVG file as input and produces *n* PNG files, at different sizes (the assumption is that they will be square).

It caches the PNG files, because it takes time for them to be generated in the first place.

I would not recommend using this in production (yet); it needs tests, for one thing. I have mainly factored it out as a separate package because I maintain a few WebExtensions that need this functionality.
