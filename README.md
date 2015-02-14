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
#### Manual
    mkdir -p ~/Library/Application\ Support/Avian/Bundles
    cd ~/Library/Application\ Support/Avian/Bundles
    git clone git://github.com/jameswomack/Stylus-TextMate-Bundle Stylus.tmbundle
	# If Stylus doesn't automatically show up in your Bundles menu, restart TextMate 2
#### Auto
    ./Installation/install # run from this repo



Notes:
-------------
This bundle now includes syntax highlighting as well as compiling the markup and bring up a window showing you the results as CSS. 

**Ensure that TextMate sees your global npm install in it's `$PATH` (something like `/usr/local/share/npm/bin`).**

Patches for additions are always welcome.

![screenshot](https://www.dropbox.com/s/vh3ge7cqutddkkk/Screen%20Shot%202015-02-14%20at%2011.08.47%20AM.png?raw=1)

This is based on the official Stylus bundle which bizarrely compiled the code but did not output it to a file. The impetus for this expansion was the fact that Stylus failed to recompile on changes within Express, which has happened to several other programmers as well. 

