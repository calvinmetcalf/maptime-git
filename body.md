http://calvinmetcalf.github.io/maptime-git

*Git* and *Github* for *GeoData*

By Calvin Metcalf

*Limits*

This is for:

Data less then 10MB

Preferably much less

This is an 80% solution

You can *not* jigger it to work for your 300MB data inventory

Don't waste your time

Use it for your 12 other datasets that are 800k or less

*also*

just putting it out there

nobody gives a shit about authoritative data sources except their publisher

*nobody*

bear that in mind before asking your question about preventing forks

you'll understand when we get there

*Git*

Version Control

Distributed

No Central Source

Unless you want one.

As complex as you want it to be

developed by linux maintainers so that large groups could code together via email

*lingo*

commit: a set of changes

they are cumulative

like drafts of a paper

you can hope back to the state your repo was at by going to the commit

and also compare the difference between commits to see what was changed

the basic 'unit' of git

repository (repo): a place where you put code (or data or anything)

you can have a repository on your computer

and one on another one (like a server)

you edit your repo

then commit the changes (with a message)

then push the changes from your local computer to the server

its like editing a word doc

saving a draft

and then posting the new draft with a note

except if 8 people are all doing it for the same document it doesn't suck

*github*

a place to store your git repo

big deal right?

code view

evolved into data view

and difs of data

*next slides few slides from Bill Morris's presentation on git*

How to github

step one

[Sign up for a github account](https://github.com/)

![signup](https://farm6.staticflickr.com/5614/15466041880_ce519038ff_b.jpg)

That's it!

(not really; we have some work to do. But is **is** that easy to get started.)

For good measure, install the github app (aka CodeBeGone)

([for mac](https://mac.github.com/) & [for windows](https://windows.github.com/))

any geojson or topojson (under 10mb) will be rendered

free hosting of static sites

to get data in you can use [esri2open](https://github.com/project-open-data/esri2open)

or [geojson.io](http://geojson.io)