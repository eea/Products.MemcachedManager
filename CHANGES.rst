Changelog
=========

1.1 - Unreleased
----------------

* Support pylibmc 1.2.0 and up, by not setting the removed cache_lookup
  behaviour.
  [mj]

* Avoid deprecation warnings for DTMLFile and md5 where possible.
  [mj]

* Remove deprecation warning on from Globals import InitializeClass
  [toutpt]


1.1b2 - 2010-10-19
------------------

* Use aq_get instead of getattr for getting acquired REQUEST.
  Thanks to Vincent Fretin for pointing it out.
  [tesdal]


1.1b1 - 2010-10-10
------------------

* Fixed a bug with an assumption that object always has REQUEST available.
  [tesdal]

* Enable pylibmc compression
  [tesdal]

* Improve pylibmc support by handling MemcachedError.
  [tesdal]


1.0rc2 - March 25, 2009
-----------------------

* Remove cmemcache support
  Add pylibmc support
  Optimized cache lookup code
  [tesdal]


1.0rc1 - Janunary 13, 2009
--------------------------

* Get rid of the entry list. For invalidation we bump
  a counter instead.
  [tesdal]

* Use pickle protocol 2.
  [tesdal]


1.0b2 - August 25, 2008
-----------------------

* Mirror invalidation support
  [tesdal]


1.0b1 - June 5, 2008
--------------------

* Repackage MemcachedManager as an egg.
  [wichert]

* Remove old style test setup and update it to current conventions.
  [wichert]
