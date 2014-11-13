[![Made By Teamed.io](http://img.teamed.io/btn.svg)](http://www.teamed.io)
[![DevOps By Rultor.com](http://www.rultor.com/b/teamed/pdd)](http://www.rultor.com/p/teamed/pdd)

[![Build Status](https://travis-ci.org/teamed/pdd.svg)](https://travis-ci.org/teamed/pdd)
[![Gem Version](https://badge.fury.io/rb/pdd.svg)](http://badge.fury.io/rb/pdd)
[![Dependency Status](https://gemnasium.com/teamed/pdd.svg)](https://gemnasium.com/teamed/pdd)
[![Code Climate](http://img.shields.io/codeclimate/github/teamed/pdd.svg)](https://codeclimate.com/github/teamed/pdd)
[![Coverage Status](https://img.shields.io/coveralls/teamed/pdd.svg)](https://coveralls.io/r/teamed/pdd)

Install it first:

```bash
$ sudo apt-get install ruby1.9.1-dev
$ gem install pdd
```

Run it locally and read its output:

```bash
$ pdd --help
```

Every puzzle has to be formatted like this (pay attention
to the leading space in every consecutive line):

```java
/**
 * @todo #234:15m/DEV This is something to do later
 *  in one of the next releases. I can't figure out how
 *  how to implement it now, that's why the puzzle.
 */
```

It starts with `@todo`, followed by a space and a puzzle marker.
Possible formats of puzzle markers:

```
#224
#TEST-13
#55:45min
#67/DES
#678:40m/DEV
```

Read this article about
[Puzzle Drive Development](http://www.yegor256.com/2009/03/04/pdd.html).
