#XMPP to popup

This simple script logs into a specified Jabber account, approves all incoming
subscription requests, and shows every incoming message in a popup window on
the bottom right of your desktop. My intended use case of this is for
interactive comments during my lectures. Not sure if this will work, worth a
shot. :)

## Dependencies:

* [Wokkel](http://wokkel.ik.nu/) (>= 0.7.1) (and, in turn, [Twisted Words](https://twistedmatrix.com/trac/wiki/TwistedWords))
* [PyGObject](https://wiki.gnome.org/action/show/Projects/PyGObject?action=show)
