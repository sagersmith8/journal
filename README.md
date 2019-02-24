[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![github license](https://img.shields.io/github/license/sagersmith8/journal.svg)](https://github.com/sagersmith8/journal/blob/master/LICENSE)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/sagersmith8/journal/graphs/commit-activity)
[![github release](https://img.shields.io/github/release/sagersmith8/journal.svg)](https://github.com/sagersmith8/journal/releases/)
[![github all releases](https://img.shields.io/github/downloads/sagersmith8/journal/total.svg)](https://github.com/sagersmith8/journal/releases/)


[![codecov](https://codecov.io/gh/sagersmith8/journal/branch/master/graph/badge.svg)](https://codecov.io/gh/sagersmith8/journal)
[![Build Status](https://travis-ci.com/sagersmith8/journal.png)](https://travis-ci.com/sagersmith8/journal)
[![github contributors](https://img.shields.io/github/contributors/sagersmith8/journal.svg)](https://github.com/sagersmith8/journal/graphs/contributors/)
[![github issues](https://img.shields.io/github/issues/sagersmith8/journal.svg)](https://github.com/sagersmith8/journal/issues/)
[![github issues-closed](https://img.shields.io/github/issues-closed/sagersmith8/journal.svg)](https://github.com/sagersmith8/journal/issues?q=is%3Aissue+is%3Aclosed)
[![github pull-requests](https://img.shields.io/github/issues-pr/sagersmith8/journal.svg)](https://github.com/sagersmith8/journal/pull/)
[![github pull-requests closed](https://img.shields.io/github/issues-pr-closed/sagersmith8/journal.svg)](https://github.com/sagersmith8/journal/pull/)



# journal
---

Engineering notebook designed for agile based software engineering

- [installation](#installation)
- [dependencies](#dependencies)
- [dev-dependencies](#dev-dependencies)
- [usage](#usage)
- [versions](#versions)
  - [0.0.1](#0.0.1)
- [license](#licence)

## installation
---

```bash
pip install journal
``` 

## dependencies
---
[python 2.7](https://www.python.org/download/releases/2.7/)
[colorama](https://pypi.org/project/colorama/)
[GitPython](https://pypi.org/project/GitPython/)


## dev-dependencies
--
[codecov](https://pypi.org/project/codecov/)
[flake8](https://pypi.org/project/flake8/)
[mock](https://pypi.org/project/mock/)
[nose](https://pypi.org/project/nose/)

## usage
---
```bash
$ journal -h
usage: journal [-h] [-t] [-d] [-n] [-c] [-s] [-j] [-b BEFORE] [-a AFTER]
               [entry]

        journal makes commits to repos in the following locations:
        	journal location: /Users/sagesmith/.journal
        	notes location: /Users/sagesmith/.journal/.notes
        	ticket location: /Users/sagesmith/.journal/.ticket
        	todo location: /Users/sagesmith/.journal/.todo

positional arguments:
  entry                 entry to enter in journal

optional arguments:
  -h, --help            show this help message and exit
  -t, --ticket          specifies ticket journal
  -d, --do              specifies todo journal
  -n, --note            specifies note journal
  -s, --standup         prints stand up
  -j, --journal         specifies entire journal
  -b BEFORE, --before BEFORE
                        specifies to grab standup logs before entered date
  -a AFTER, --after AFTER
                        specifies to grab standup logs after entered date

made by sage smith
```

## versions
---

#### 0.0.1
Initial release. Includes `journal` and `standup` commands

## license
---
[Apache Commons 2.0](https://www.apache.org/licenses/LICENSE-2.0)
