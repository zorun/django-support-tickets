=============================
Django Support Tickets
=============================

.. image:: https://img.shields.io/badge/Bazzite-project-blue.svg?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAxNi4wLjAsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjwhRE9DVFlQRSBzdmcgUFVCTElDICItLy9XM0MvL0RURCBTVkcgMS4xLy9FTiIgImh0dHA6Ly93d3cudzMub3JnL0dyYXBoaWNzL1NWRy8xLjEvRFREL3N2ZzExLmR0ZCI%2BDQo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB3aWR0aD0iMzAyLjc4NnB4IiBoZWlnaHQ9IjI5MC4yNjZweCIgdmlld0JveD0iMC45MDUgMC40OTggMzAyLjc4NiAyOTAuMjY2IiBlbmFibGUtYmFja2dyb3VuZD0ibmV3IDAuOTA1IDAuNDk4IDMwMi43ODYgMjkwLjI2NiINCgkgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI%2BDQo8dGl0bGU%2BbG9nb19yZWN0YW5nbGU8L3RpdGxlPg0KPGRlc2M%2BQ3JlYXRlZCB3aXRoIFNrZXRjaC48L2Rlc2M%2BDQo8ZyBpZD0iUGFnZS0xIj4NCgk8ZyBpZD0ibG9nb19yZWN0YW5nbGUiPg0KCQk8ZyBpZD0iR3JvdXAiPg0KCQkJPGcgaWQ9IkNsaXBwZWRfN18iPg0KCQkJCTxwb2x5Z29uIGlkPSJTaGFwZV83XyIgZmlsbD0iI0ZGRkZGRiIgcG9pbnRzPSIxMTAuMTIzLDAuNjAzIDAuOTA1LDIxNC42NjEgNDIuMzMzLDI5MC43NjQgMTkzLjI0NSwwLjQ5OCAJCQkJIi8%2BDQoJCQk8L2c%2BDQoJCQk8ZyBpZD0iQ2xpcHBlZF84XyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDIxNC4wMDAwMDApIj4NCgkJCQk8cG9seWxpbmUgaWQ9IlNoYXBlXzhfIiBmaWxsPSIjRkZGRkZGIiBwb2ludHM9IjQyLjYxLDc2Ljc2NCAxNTIuNTEsNDguMTM1IDE1Mi4zOTgsMC40NjcgMC45MDksMC42NjEgCQkJCSIvPg0KCQkJPC9nPg0KCQkJPGcgaWQ9IkNsaXBwZWRfOV8iIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE1MS4wMDAwMDAsIDIxNC4wMDAwMDApIj4NCgkJCQk8cG9seWxpbmUgaWQ9IlNoYXBlXzlfIiBmaWxsPSIjRkZGRkZGIiBwb2ludHM9IjEwOC45ODYsNzYuMzIzIDAuMTk4LDQ4LjEzNyAwLjA4OCwwLjQ2OSAxNTIuNjkxLDAuMjc1IAkJCQkiLz4NCgkJCTwvZz4NCgkJCTxnIGlkPSJDbGlwcGVkXzEwXyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTEwLjAwMDAwMCwgMC4wMDAwMDApIj4NCgkJCQk8cG9seWdvbiBpZD0iU2hhcGVfMTBfIiBmaWxsPSIjRkZGRkZGIiBwb2ludHM9IjAuMTIzLDAuNjAzIDE1MC4wNzcsMjkwLjMyMyAxOTMuNjkxLDIxNC4yNzUgODMuMjQ1LDAuNDk4IAkJCQkiLz4NCgkJCTwvZz4NCgkJPC9nPg0KCTwvZz4NCjwvZz4NCjwvc3ZnPg0K
    :target: https://github.com/bazzite/scrits-django
    :alt: Bazzite Project

.. image:: https://badge.fury.io/py/django-support-tickets.svg
    :target: https://badge.fury.io/py/django-support-tickets

.. image:: https://travis-ci.org/bazzite/django-support-tickets.svg?branch=master
    :target: https://travis-ci.org/bazzite/django-support-tickets

.. image:: https://codecov.io/gh/bazzite/django-support-tickets/branch/master/graph/badge.svg
    :target: https://codecov.io/gh/bazzite/django-support-tickets

Another Support Tickets Django App

Documentation
-------------

The full documentation is at https://docs.bazzite.com/django-support-tickets/.

Quickstart
----------

Install Django Support Tickets::

    pip install django-support-tickets

Add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'support_tickets.apps.SupportTicketsConfig',
        ...
    )

Add Django Support Tickets's URL patterns:

.. code-block:: python

    from support_tickets import urls as support_tickets_urls


    urlpatterns = [
        ...
        url(r'^', include(support_tickets_urls)),
        ...
    ]

Features
--------

* TODO

Running Tests
-------------

Does the code actually work?

::

    source <YOURVIRTUALENV>/bin/activate
    (myenv) $ pip install tox
    (myenv) $ tox

Credits
-------

Tools used in rendering this package:

*  Cookiecutter_
*  `cookiecutter-djangopackage`_

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`cookiecutter-djangopackage`: https://github.com/pydanny/cookiecutter-djangopackage
