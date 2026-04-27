ByteSize
========

Almost identical to github.com/inhies/go-bytesize

But with recpect to IEC standard:

```
1 KB = 1000 B
1 MB = 1000 KB
...

1 KiB = 1024 B
1 MiB = 1024 KiB
...
```

Due to original repo breaking compatibility (it is `1KB = 1024B` there),
this project can not be merged into original. Feel free to use and make issues / PRs. 

### Original README

Bytesize is a package for working with measurements of bytes. Using this package
allows you to easily add 100KB to 4928MB and get a nicely formatted string
representation of the result.

[![Go Reference](https://pkg.go.dev/badge/github.com/inhies/go-bytesize.svg)](https://pkg.go.dev/github.com/inhies/go-bytesize)
[![Build Status](https://travis-ci.org/inhies/go-bytesize.png)](https://travis-ci.org/inhies/go-bytesize)
[![Coverage Status](https://coveralls.io/repos/inhies/go-bytesize/badge.svg?branch=master&service=github)](https://coveralls.io/github/inhies/go-bytesize?branch=master)

Usage
-----

Check the built in documentation for examples using the godoc link above or by
running godoc locally. 
