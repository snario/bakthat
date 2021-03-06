.. _api:

Bakthat API
===========

Bakthat
-------

These functions are called when using bakthat in command line mode and are the foundation of the bakthat module.


.. module:: bakthat

backup
~~~~~~

.. autofunction:: backup

restore
~~~~~~~

.. autofunction:: restore

info
~~~~

.. autofunction:: info

show
~~~~

.. autofunction:: show

delete
~~~~~~

.. autofunction:: delete

delete_older_than
~~~~~~~~~~~~~~~~~

.. autofunction:: delete_older_than

rotate_backups
~~~~~~~~~~~~~~

.. autofunction:: rotate_backups


Backends
--------

BakthatBackend
~~~~~~~~~~~~~~

.. autoclass:: bakthat.backends.BakthatBackend
   :members:

GlacierBackend
~~~~~~~~~~~~~~

.. autoclass:: bakthat.backends.GlacierBackend
   :members:

S3Backend
~~~~~~~~~

.. autoclass:: bakthat.backends.S3Backend
   :members:

SwiftBackend
~~~~~~~~~~~~

.. autoclass:: bakthat.backends.SwiftBackend
   :members:


RotationConfig
~~~~~~~~~~~~~~

.. autoclass:: bakthat.backends.RotationConfig
   :members:

Helper
------

BakHelper
~~~~~~~~~

.. autoclass:: bakthat.helper.BakHelper
   :members:

KeyValue
~~~~~~~~

.. autoclass:: bakthat.helper.KeyValue
   :members:

Sync
----

BakSyncer
~~~~~~~~~

.. autoclass:: bakthat.sync.BakSyncer
   :members:

bakmanager_hook
~~~~~~~~~~~~~~~

.. autofunction:: bakthat.sync.bakmanager_hook

Utils
-----

.. autofunction:: bakthat.utils._timedelta_total_seconds

.. autofunction:: bakthat.utils._interval_string_to_seconds

Models
------

.. autoclass:: bakthat.models.Backups
   :members:


.. autoclass:: bakthat.models.Inventory
   :members:


.. autoclass:: bakthat.models.Jobs
   :members:


.. autoclass:: bakthat.models.Config
   :members:
