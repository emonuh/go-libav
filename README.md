# go-libav

[![License](http://img.shields.io/badge/license-MIT-red.svg?style=flat)](https://github.com/imkira/go-libav/blob/master/LICENSE.txt)
[![GoDoc](https://godoc.org/github.com/imkira/go-libav?status.svg)](https://godoc.org/github.com/imkira/go-libav)
[![Build
Status](http://img.shields.io/travis/imkira/go-libav.svg?style=flat)](https://travis-ci.org/imkira/go-libav)
[![Coverage](http://img.shields.io/codecov/c/github/imkira/go-libav.svg?style=flat)](https://codecov.io/github/imkira/go-libav)

[Go](https://golang.org) language bindings for [ffmpeg](https://ffmpeg.org)
libraries.

This is still a work in progress. This package still lacks a lot of the libav's
functionality. Please expect many additions/changes in the future.

# Why

I am aware of other Go language bindings for ffmpeg.
The reason I decided to build go-libav was because I wanted to have:

- A more Object-Oriented Programming approach.
- A more Go-like approach to error handling.
- Easier garbage collection.

# Installation

First, install ffmpeg libraries on your system.
I have tested it with ffmpeg 2.6.4 and later.

Then, open the terminal and install the following packages:

```
go get -u github.com/imkira/go-libav/avcodec
go get -u github.com/imkira/go-libav/avfilter
go get -u github.com/imkira/go-libav/avformat
go get -u github.com/imkira/go-libav/avutil
```

# Documentation

For advanced usage, make sure to check the following documentation:

- [avcodec](http://godoc.org/github.com/imkira/go-libav/avcodec)
- [avfilter](http://godoc.org/github.com/imkira/go-libav/avfilter)
- [avformat](http://godoc.org/github.com/imkira/go-libav/avformat)
- [avutil](http://godoc.org/github.com/imkira/go-libav/avutil)

# Examples

Coming soon.

# Contribute

Found a bug? Want to contribute and add a new feature?

Please fork this project and send me a pull request!

# License

go-libav is licensed under the MIT license:

www.opensource.org/licenses/MIT

# Copyright

Copyright (c) 2015 Mario Freitas. See
[LICENSE](http://github.com/imkira/go-libav/blob/master/LICENSE)
for further details.
