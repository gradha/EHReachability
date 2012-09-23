==========================
Apple's reachability class
==========================

:author: Grzegorz Adam Hankiewicz <gradha@imap.cc>

.. contents::

.. section-numbering::

.. raw:: pdf

   PageBreak oneColumn

General
=======

If you are an iOS developer and want to know the state of the network, you are
likely going to reach for the source Apple provides with its **Reachability**
sample. This sample provides a drop in class which tells you about the status
of the network. Simply add to your project and use.

This is yet another copy but stored at github so I can refer to it as a
submodule and avoid the copy/paste work when theres an update. I've renamed the
class to have a prefix so it doesn't clash with other libraries including their
own version (yes, sometimes happens). I've also added a few convenience methods
which are most likely of no use to other than me. Use diff against Apple's
original version to see all modifications.

See Apple_ReadMe.txt file or the source code to find out what version this repo
has been updated to. Browse my github profile at https://github.com/gradha for
other source code.  You can find other of my creations on the App Store under
my Electric Hands Software brand
(http://itunes.apple.com/artist/electric-hands-software/id325946567) which you
can also find at http://elhaso.com/.


License
=======

This happens to be licensed by Apple, see the source code comments. Essentially
you are allowed to shot yourself in the foot with this from multiple network
locations at the same time.
