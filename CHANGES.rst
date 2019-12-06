==============
Change History
==============

0.4.0.post1 (2019-12-06)
------------------------

- Fix change log on PyPI.


0.4.0 (2019-12-06)
------------------

- Use new Python 2.6/3.x compatible exception syntax. (This does not mean that
  this package is already Python 3 compatible.)


0.3.1 (2012-04-27)
------------------

- When binding the monitor to a Unix-domain socket, remove an existing
  socket at the same path so the bind is successful.  This may affect
  existing usage with respect to zopectl debug behavior, but will be
  more predictable.


0.3.0 (2011-12-12)
------------------

- Added a simplified registration interface.


0.2.1 (2011-12-10)
------------------

- Added an ``address`` option to ``start`` to be able to specify an adapter
  to bind to.

- ``start`` now returns the address being listened on, which is useful
  when binding to port 0.

- Using Python's ``doctest`` module instead of depreacted
  ``zope.testing.doctest``.


0.2.0 (2009-10-28)
------------------

- Add the "MORE" mode so commands can co-opt user interaction


0.1.2 (2008-09-15)
------------------

- Bugfix: The z3monitor server lacked a handle_close method, which
  caused errors to get logged when users closed connections before
  giving commands.


0.1.1 (2008-09-14)
------------------

- Bugfix: fixed and added test for regression in displaying tracebacks.


0.1.0 (2008-09-14)
------------------

Initial release
