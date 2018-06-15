pickleDB
--------

pickleDB is lightweight, fast, and simple database based on the `simplejson <https://pypi.python.org/pypi/simplejson/>`_ module. And it's BSD licensed!


pickleDB is Fun
```````````````

    >>> import pickledb

    >>> db = pickledb.load('test.db', False)

    >>> db.set('key', 'value')

    >>> db.get('key')
    'value'

		>>> db.getPattern(pattern="prefix_")
    ['prefix_foo','prefix_bar']

    >>> db.dump()
    True


Easy to Install
```````````````

    $ pip install pickledb


Links
`````

* `website <http://packages.python.org/pickleDB/>`_
* `documentation <http://packages.python.org/pickleDB/commands.html>`_
* `pypi
  <http://pypi.python.org/pypi/pickleDB>`_
