.. :changelog:

History
=======

x.x.x (xxxx-xx-xx)
------------------
New features:

* Japanese language support.


0.3.4 (2016-03-03)
------------------
Improvements:

* Fixed broken version 0.3.3 by excluding latest python-dateutil version.

0.3.3 (2016-02-29)
------------------
New features:

* Finnish language support.

Improvements:

* Faster parsing with switching to regex module.
* `RETURN_AS_TIMEZONE_AWARE` setting to return tz aware date object.
* Fixed conflicts with month/weekday names similarity across languages.

0.3.2 (2016-01-25)
------------------
New features:

* Added Hijri Calendar support.
* Added settings for better control over parsing dates.
* Support to convert parsed time to the given timezone for both complete and relative dates.

Improvements:

* Fixed problem with caching :func:`datetime.now` in :class:`FreshnessDateDataParser`.
* Added month names and week day names abbreviations to several languages.
* More simplifications for Russian and Ukranian languages.
* Fixed problem with parsing time component of date strings with several kinds of apostrophes.


0.3.1 (2015-10-28)
------------------
New features:

* Support for Jalali Calendar.
* Belarusian language support.
* Indonesian language support.


Improvements:

* Extended support for Russian and Polish.
* Fixed bug with time zone recognition.
* Fixed bug with incorrect translation of "second" for Portuguese.


0.3.0 (2015-07-29)
------------------
New features:

* Compatibility with Python 3 and PyPy.

Improvements:

* `languages.yaml` data cleaned up to make it human-readable.
* Improved Spanish date parsing.


0.2.1 (2015-07-13)
------------------
* Support for generic parsing of dates with UTC offset.
* Support for Tagalog/Filipino dates.
* Improved support for French and Spanish dates.


0.2.0 (2015-06-17)
------------------
* Easy to use `parse` function
* Languages definitions using YAML.
* Using translation based approach for parsing non-english languages. Previously, :mod:`dateutil.parserinfo` was used for language definitions.
* Better period extraction.
* Improved tests.
* Added a number of new simplifications for more comprehensive generic parsing.
* Improved validation for dates.
* Support for Polish, Thai and Arabic dates.
* Support for :mod:`pytz` timezones.
* Fixed building and packaging issues.


0.1.0 (2014-11-24)
------------------

* First release on PyPI.
