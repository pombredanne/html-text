============
HTML to Text
============


.. image:: https://img.shields.io/pypi/v/html-text.svg
        :target: https://pypi.python.org/pypi/html-text

.. image:: https://img.shields.io/travis/TeamHG-Memex/html-text.svg
        :target: https://travis-ci.org/TeamHG-Memex/html-text


Extract text from HTML


* Free software: MIT license


Install
-------

Install with pip::

    pip install html-text

The package depends on lxml, so you might need to install some additional
packages: http://lxml.de/installation.html


Usage
-----

Extract text from HTML::

    >>> import html_text
    >>> text = html_text.extract_text(u'<h1>Hey</h1>')
    u'Hey'


Credits
-------

The code is extracted from utilities used in several projects, written by Mikhail Korobov.
