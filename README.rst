UtahWatch
==========

UtahWatch tracks the HTTPS support of websites of Utah-based entities. UtahWatch is part of the `SecureUtah.org`_ website.

This repo is for the config files, templates, and scripts that are used to generate the UtahWatch website.  The output files are then moved to ``https://github.com/SecureUtah/utahwatch`` to be served via GitHub Pages.

UtahWatch is a fork of `HTTPSWatch`_. The HTTPSWatch code is available on `GitHub`_ and was originally created by Benjamin Peterson.


-----------

The following instructions are taken from the HTTPSWatch README and apply to this project:

The code is fairly simple. Python 3.4 is required. The ``check_https.py`` script
generates a small static site from JSON data in the ``config/`` directories and
Jinja2 templates from the ``templates/`` directory.

If you edit the HTML, please do not wrap HTML lines. (Paragraphs should be on
one line.)

Once ``check_https.py`` has been run, you can run ``testing_server.py`` to view
the website at ``localhost:8000``.


.. _SecureUtah.org: http://secureutah.org
.. _HTTPSWatch: https://httpswatch.com
.. _GitHub: https://github.com/gutworth/httpswatch
