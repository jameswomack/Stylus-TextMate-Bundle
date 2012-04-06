Stylus.tmbundle
---------------------

A **TextMate Bundle** for the **Stylus** programming language. 
    

Installation:
-------------
###Textmate 1
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/jameswomack/Stylus-TextMate-Bundle Stylus.tmbundle

###Textmate 2
    cd /Applications/TextMate.app/Contents/SharedSupport/Bundles
    git clone git://github.com/jameswomack/Stylus-TextMate-Bundle Stylus.tmbundle

The bundle does not yet include syntax highlighting, but does compile the markup and bring up a window showing you the results as CSS.

Patches for additions are always welcome.

![screenshot](http://cirrostratusco.com/i/github/stylus-textmate-bundle.png)

This is based on the official Stylus bundle which bizarrely compiled the code but did not output it to a file. The impetus for this expansion was the fact that Stylus failed to recompile on changes within Express, which has happened to several other programmers as well. 

