# Docker and Django
These are notes I write for myself on how to host [Django](http://djangoproject.org) projects with [Docker](#haha-this-is-not-a-link-i-am-so-funny) in a nice way.

You should not believe anything in this file. 

- micro services if possible
- theory: one container per app might be better
- another container for DB
- another container for vagrant
- yet another container for static files
- some sort of URL dispatcher container that maps sub-URLS to containers?