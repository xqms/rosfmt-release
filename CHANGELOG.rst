^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rosfmt
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

7.0.0 (2021-01-03)
------------------
* rename rosfmt library to rosfmt7 to prevent ABI mismatches
* Update fmt to 7.1.2
* cmake: fix ordering of internal include paths
* add new full.h header (issue: #2)
* Contributors: Max Schwarz

6.2.0 (2020-01-09)
------------------
* ensure vformat is only instantiated once -> faster compile times
* update to fmt 6.0.0
* Contributors: Max Schwarz

6.1.0 (2019-05-14)
------------------
* cmake: fix dependency tracking bugs
* update fmt to version 5.3.0
* Contributors: Max Schwarz

6.0.0 (2018-11-14)
------------------
* Major release bump to decouple rosfmt and fmt versions
* rosfmt.h: produce nicer error message if C++11 is not available
* cmake: add transitive rosconsole / roscpp deps
* README: add CMake example
* Contributors: Max Schwarz

5.2.2 (2018-10-29)
------------------
* README: syntax highlighting
* add README.md, LICENSE.txt
* initial commit - basics are working
* Contributors: Max Schwarz
