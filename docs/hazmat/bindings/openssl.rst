.. danger::

    This is a "Hazardous Materials" module. You should **ONLY** use it if
    you're 100% absolutely sure that you know what you're doing because this
    module is full of land mines, dragons, and dinosaurs with laser guns.


OpenSSL
=======

These are `CFFI`_ bindings to the `OpenSSL`_ C library.

.. data:: cryptography.hazmat.bindings.openssl.backend

    This is the exposed API for the OpenSSL bindings. It has two public
    attributes:

    .. attribute:: ffi

        This is a :class:`cffi.FFI` instance. It can be used to allocate and
        otherwise manipulate OpenSSL structures.

    .. attribute:: lib

        This is a ``cffi`` library. It can be used to call OpenSSL functions,
        and access constants.


.. _`CFFI`: http://cffi.readthedocs.org/
.. _`OpenSSL`: https://www.openssl.org/