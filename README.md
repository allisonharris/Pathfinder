# Pathfinder

Pathfinder is my default starting point for all of my builds. This is a work in progress and will be updated as my needs change.

If you see anything in here that can be improved, please help me out and let me know. 

Here's a breakdown of the folder structure used:

##css
	-This is where the compiled css will go.
	Files here never really get touched.
	All of the code writing will happen in the .scss files, then will be compiled down here using codekit.
##helpers
 	-These are the tools I use to set the defaults for a site.
 	These files are gathered from a few different places, then adjusted to meet my needs.
##img
	-Self explanatory. I'm now separating the inline styles from styles that are referenced in the css.
##parts
	-These are the building blocks that will be used to build out a site.
	The files naming convention is based on SMACSS by Jonathan Snook (@snookca)

#Pathfinder is a combination of many different resources:

##Vanilla
 - Much of this is based on [_Vanilla_](http://github.com/csswizardry/vanilla) by [Harry Roberts](https://github.com/csswizardry), but my version only contains the base styles that I've needed for my projects so far. 
 
  - I encourage you to check out [Inuit.css](https://github.com/csswizardry/inuit.css) for a more comprehensive framework.

##SMACSS
 - The file names in the _parts_ folder are taken from [SMACSS](http://smacss.com/) by Jonathan Snook [@snookca](http:www.twitter.com/snookca) , which is an essential read about css architecture. He divides his styles into base, layout, modules and states. I'll likely abstract it a bit more as I go along, but I think this is a fantastic place to start.

 - SMACSS is much more than simply dividing up and naming files though, so please do yourself a favor and read it.

## The [micro clearfix](http://nicolasgallagher.com/micro-clearfix-hack/) & [Normalize](https://github.com/necolas/normalize.css) are both from [Nicolas Gallagher.](https://github.com/necolas)


	This is my **front-end starting point**. There are many like it, but this one is mine.
	My **Pathfinder** is my best friend.
	It is my life. I must master it as I must master my life.
	My **Pathfinder**, without me, is useless.
	Without my **Pathfinder**, I am useless
	...