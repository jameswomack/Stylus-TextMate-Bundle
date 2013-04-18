Stylus.tmbundle
---------------------

A **TextMate Bundle** for the **Stylus** programming language. 
    

Installation:
-------------
###Textmate 1
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/jameswomack/Stylus-TextMate-Bundle Stylus.tmbundle
	osascript -e 'tell app "TextMate" to reload bundles'

###Textmate 2
    cd ~/Library/Application\ Support/Avian/Bundles
    git clone git://github.com/jameswomack/Stylus-TextMate-Bundle Stylus.tmbundle
	# If Stylus doesn't automatically show up in your Bundles menu, restart TextMate 2

This bundle now includes syntax highlighting as well as compiling the markup and bring up a window showing you the results as CSS. 

**Ensure that TextMate sees your global npm install in it's `$PATH` (something like `/usr/local/share/npm/bin`).**

Patches for additions are always welcome.

![screenshot](http://cirrostratusco.com/i/github/stylus-textmate-bundle.png)

This is based on the official Stylus bundle which bizarrely compiled the code but did not output it to a file. The impetus for this expansion was the fact that Stylus failed to recompile on changes within Express, which has happened to several other programmers as well. 

