Performing I/O
==============

Sockets and networking
----------------------

.. module:: trio.socket

.. autoclass:: trio.socket.SocketType()

   .. method:: connect


The abstract Stream API
-----------------------

.. currentmodule:: trio

.. autoclass:: AsyncResource
   :members:

.. autoclass:: SendStream
   :members:

.. autoclass:: RecvStream
   :members:

.. autoclass:: Stream
   :members:


TLS support
-----------

`Not implemented yet! <https://github.com/njsmith/trio/issues/9>`__


Subprocesses
------------

`Not implemented yet! <https://github.com/njsmith/trio/issues/4>`__


Signals
-------

.. currentmodule:: trio

.. autofunction:: catch_signals
   :with: