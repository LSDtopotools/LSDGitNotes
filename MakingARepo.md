-----------------------------------
title: MakingARepo
layout: default
-----------------------------------


Making a repo
====================================

This explains how to make a new repository. It won't be that detailed since you should look at [software carpentry](http://www.software-carpentry.org/v5/novice/git/) 
or our [in-house lessons](http://www.geos.ed.ac.uk/~smudd/NMDM_Course/html/index.html) for more detail. 

However, the steps to make a new repository hosted on github are:

* If you are trying to make a repo within LSDtopotools, make sure you are on the [LSDtopotools page](https://github.com/LSDtopotools). 
* From that page, click on `New repository`. It is a green button. 
* I find it easier to make the `readme.md` myself and add it to the repo (gitub will ask you if you want to make it yourself). 
* Now make a directory for the new repository on your computer. 
* Go into that directory and `git init` the repo. Then `git add` some files (at first the `readme.md` is important to add). 
* Then add the remote (githib will tell you the http address of it). This will result in a command like:
```git remote add origin https://github.com/LSDtopotools/FunkMonkeyScripts.git```
* I don't know why this happens by my computer doesn't like an origin of `origin, so I use:
```git remote add myorigin https://github.com/LSDtopotools/FunkMonkeyScripts.git```
* Then push the changes:
```git push -u myorigin master```. If you called your origin something else you will have to use that name. 