.. _requirements:

***************************
HuskyCMS Requirements
***************************

.. _requirements.introduction:

Introduction
------------

HuskyCMS requires a *PHP* 5 interpreter with a web server configured to handle *PHP* scripts correctly. Some
features require additional extensions or web server features; in most cases the framework can be used without
them, although performance may suffer or ancillary features may not be fully functional. An example of such a
dependency is mod_rewrite in an Apache environment, which can be used to implement "pretty *URL*'s" like
"``http://www.example.com/user/edit``". If mod_rewrite is not enabled, Zend Framework can be configured to support
*URL*'s such as "``http://www.example.com?controller=user&action=edit``". Pretty *URL*'s may be used to shorten
*URL*'s for textual representation or search engine optimization (*SEO*), but they do not directly affect the
functionality of the application.

.. _requirements.version:

PHP Version
^^^^^^^^^^^

Zend recommends the most current release of *PHP* for critical security and performance enhancements, and currently
supports *PHP* 5.2.4 or later.
