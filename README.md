#XMPP to popup

This simple script logs into a specified Jabber account, approves all incoming
subscription requests, and shows every incoming message in a popup window on
the bottom right of your desktop. My intended use case of this is for
interactive comments during my lectures. The messages can optionally time out
after a set period. Not sure if this will work, but I think it's worth a shot.
:)

## Dependencies

* [Wokkel](http://pypi.python.org/pypi/wokkel) (>= 0.7.1) (and, in turn, [Twisted Words](https://twistedmatrix.com/trac/wiki/TwistedWords))
* [PyGObject](https://wiki.gnome.org/action/show/Projects/PyGObject?action=show)

## License

Just in case anyone cares, xmpp-popup is licensed to you under the MIT/X
Consortium license:

Copyright (c) 2014 Andreas Klöckner

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
