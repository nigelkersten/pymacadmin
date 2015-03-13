A collection of Python utilities for Mac OS X system administration.

The PyMacAdmin project started as a collaboration between [Chris Adams](http://improbable.org/chris) and [Nigel Kersten](http://explanatorygap.net) to develop a replacement for the unsupported 'kicker' feature included in OS X prior to 10.5. That replacement eventually became [crankd](http://pymacadmin.googlecode.com/git/bin/crankd.py), which provides a way to execute Python code or a shell script in response to many system events: network changes, filesystem activity, application launching, etc.

We've also added utilities to [create network locations](http://pymacadmin.googlecode.com/git/bin/create-location.py),
[manage DirectoryServices](http://pymacadmin.googlecode.com/git/pymacds-dist/),
[manage proxy settings](http://pymacadmin.googlecode.com/git/bin/set-proxy.py) or [update AirPort passwords](http://pymacadmin.googlecode.com/git/bin/airport-update.py) using our [Keychain](http://pymacadmin.googlecode.com/git/lib/PyMacAdmin/Security/Keychain.py) wrapper.