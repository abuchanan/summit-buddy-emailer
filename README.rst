====================
Summit Buddy Emailer
====================

Given a CSV list of buddies, send an email introducing summit buddies to eachother.

Requirements
============

* python 2.6
* local SMTP server

CSV format
==========

::

    firstname1, lastname1, email1, firstname2, lastname2, email2

Use
===

::

    python emailer.py recipients.csv
