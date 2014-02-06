.. Praekelt Patterns documentation master file, created by
   sphinx-quickstart on Fri Jul  5 19:27:01 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Praekelt Patterns!
==================

Naming things is hard, naming things consistently is even harder.
The goal of this patterns repository is to help all stake holders in a
project to know and understand what we call the individual parts that
together make up the things we build.

Patterns described in this repository should:

1. Have a short name.
2. Have a paragraph (with or without illustration) describing
   the pattern. The paragraph should be suitable for non-technical
   people to understand and re-use when describing possible solutions
   to client problems.
3. A link to a sample implementation of the pattern. The sample
   implementation should have tests and be ready for a developer
   to look at understand and apply.

.. note::

    You are free to contribute to this repository, it is automatically
    published from changes made in the the GitHub
    `patterns repository <https://github.com/praekelt/patterns/>`_.
    The full backlog of things that may possibly need to be described
    is listed in the :doc:`patterns-backlog`. Feel free to grab any of
    those and start work on it. Remember to remove it from the backlog
    when finished.


Mobi & Web Patterns
-------------------

These are a collection of patterns that mostly apply to Mobi & Web sites
we develop.

.. toctree::
   :maxdepth: 1

   age-gateway.rst

Messaging & USSD Patterns
-------------------------

These are a collection of patterns that apply to applications designed
for messaging. The code examples mostly all apply for Vumi_.


.. toctree::
  :maxdepth: 1

  states/card-stack.rst
  states/paged-result-set.rst
  states/language-choice.rst

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. _Vumi: http://www.vumi.org/
