About
=====

This could be a blog for presenting the greatest Plone add-ons with a
step-by-step screenshots for how to use them in your Plone projects (usually,
with only a few mouse clicks).

This is an experimental a Sphinx-built blog written in ReStructuredText being
built, including annotated screenshots generated from embedded Robot Framework
acceptance tests describing a Plone add-on. (Technically, each blog post could
present different add-ons.)

.. raw:: html

       <p style="text-align: center;"><iframe width="420" height="315" src="http://www.youtube.com/embed/cYN5tQJ3xtc" frameborder="0" allowfullscreen></iframe></p>

Fork this blog at: http://github.com/datakurre/elvenmagic/

Technologies
------------

* `sphinxcontrib-robotframework`_ is a `Robot Framework`_ integration for
  Sphinx.

* `robotframework-selenium2screenshots`_ is a PIL_ and jQuery-based screenshot
  annotation and cropping library for Robot Framework.  It requires also
  `robotframework-selenium2library`_.

* `plone.app.robotframework`_ allows to server Plone test fixtures directly
  from Robot Framework test suites.

* Tinkerer_ is a blogging engined built on top of Sphinx_.

.. _sphinxcontrib-robotframework: http://pypi.python.org/pypi/sphinxcontrib-robotframework
.. _robotframework-selenium2screenshots: http://pypi.python.org/pypi/sphinxcontrib-robotframework
.. _robotframework-selenium2library: http://pypi.python.org/pypi/sphinxcontrib-robotframework
.. _plone.app.robotframework: http://pypi.python.org/pypi/plone.app.robotframework
.. _PIL: http://pypi.python.org/pypi/PIL
.. _Robot Framework: http://robotframework.org
.. _Tinkerer: http://tinkerer.me/
.. _Sphinx: http://sphinx-doc.org/

