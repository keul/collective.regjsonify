Changelog
=========


0.3.1 (unreleased)
------------------

- Nothing changed yet.


0.3.0 (2020-03-13)
------------------

- Fix compatibility with zope.schema < 4
  [mamico]
- Python 3 compatibility
  [cekk]


0.2.0 (2015-08-25)
------------------

- Recusively traverse all of the interface's parents attributes
  [keul]
- Added an ``IObject`` field adapter. There's no more need that the
  persistent field implements another interface (see changes in tests).
  Also: custom IObject derived fields are now automatically supported.
  [keul]

0.1.0 (2014-05-02)
------------------

- Initial release
