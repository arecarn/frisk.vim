Frisk is a web search launcher. From within Frisk you can choose a search
engine, and enter your search terms without having to leave vim. Upon accepting
a search your default browser will open with the results of your search.

Usage
=====
:Frisk

Demo
====
A screen capture demoing Frisk can be viewed here.
http://screenr.com/Sn2H

Adding Your Own Search Engine
=============================
here's an example of how Bings Search engine infromation is stored in a plugin

    let g:Bing = {
                \'name' : 'Bing', 
                \'types':{
                \'video' : 'http://www.bing.com/video/search?q=',
                \'images' : 'http://www.bing.com/images/search?q=',
                \'web': 'http://www.bing.com/search?q='}}
    call add(g:Search, Bing)

You might see how another search engine could easily be integrated into Frisk.
If you would like another search engine added contact me and I'll see what I
can do



This is my first Vim plugin so if you have any tips feel free to contact me or
help to improve Frisk. 
