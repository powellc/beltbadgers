===============
Getting Started
===============

So, you want to build Belt Badgers locally? Or perhaps even contribute to the project development? Rad!

Belt Badgers can be setup locally in one of two ways:

--------
Makefile
--------

To use this, simply run: 

::

   make install
   make run

Assuming you have all the various libraries usually needed for Django 
installed on your box, that should work just fine. Of course, if you 
don't, those commands will fail. If you can't figure out hwo to get that
work, despair not. There's also a vagrant installer.

-------
Vagrant
-------

For this method you will need: Vagrant, Virtualbox, and ansible installed.
These are all available for Mac, Linux or Windows, so you're free to pick
your poison here. Once those requirements are met simply:

::

    vagrant up

From within the cloned directory.