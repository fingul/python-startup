Python startup files
====================

mkdir -p ~/.ipython/profile_default/startup/    
ln -sf ~/Dropbox/src/python-startup/startup.py ~/.ipython/profile_default/startup/

> why? `export PYTHONSTARTUP=xxx.py` not working properly, when using auto completion. (ex: import o [tab])


Installation
------------

Get code from Github::

    git clone git://github.com/fingul/python-startup.git ~/Dropbox/src/python-startup

Edit & commit & push
------------

    cd ~/Dropbox/src/python-startup
    git add . && git commit -m . &&  git push -u origin master

Credits
-------

This is entirely not my work (except a few fixes), all credits to the authors
as noted in the different files.
