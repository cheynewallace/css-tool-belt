The CSS Tool Belt
=============

A "hammer and nails" CSS tool kit for getting the job done.  This is not a replacement for your grid systems or CSS frameworks, but merely an additional tool for to reduce the amount of plumbing CSS you write.

This tool belt uses SASS, in SCSS syntax to generate the CSS. The outputed CSS file can be found in the /css directory.

> But I dont use SASS?

That's fine. You can just use the CSS file located in the CSS directory. I have not minified this file by default so you can actually inspect the styling your self.

# How To Use The Tool Belt #

Either include the .scss files in your project and do the compilation your self, or simply use the exported **css-tool-belt.css** in your project as regular CSS.

# Configuration #

The **config.scss** file contains options for configuratin the CSS Tool Belt. You can toggle on or off sections of the style sheet you do or do not want.  
You can also configure some basic options such as the default border radius for the .round classes.

# Suggestions #

I suggest using CodeKit when working with the tool belt. It makes compiling super simple.

# Contributing #

This is really just a toolkit I use in my projects, its not a comprehensive suite by any means. If you have some items you'd like to contribute then please, by all means do so.