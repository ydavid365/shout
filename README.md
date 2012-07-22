Shout
=====

Handles the shell scripting from Go language.

[Documentation online](http://go.pkgdoc.org/github.com/kless/shout)

#### Why?

The shell scripting gets to be no-maintainable code; its sintaxis is very
cryptic and it's very hard to debug. In addition, these negative points increase
at the same time as the size of the program grows.

Here is where [Go][] comes.

+ Go is a compiled, garbage-collected, concurrent programming language that
provides the efficiency of a statically typed compiled language with the ease of
programming of a dynamic language.

+ The compilers can target the FreeBSD, Linux, NetBSD, OpenBSD, Mac OS X (Snow
Leopard/Lion), and Windows operating systems and the 32-bit (386) and 64-bit
(amd64) x86 processor architectures, and 32-bit ARM for Linux.

+ It has a simple and clean [sintaxis][], an error handling that does code more
reliable, and a full [standard library][] although the package [os][] will be
the main one to use in system scripts.  
Whatever administrator without great knowledge about programming can built basic
scripts fastly with the help of this [tutorial for novices][].

[Go]: http://golang.org/
[sintaxis]: http://golang.org/ref/spec
[standard library]: http://golang.org/pkg/
[os]: http://golang.org/pkg/os/
[tutorial for novices]: http://go-book.appspot.com/

#### Interpreted vs Compiled

The advantage of a shell script versus a compiled program, is that it allows an
easy modification and locating of sources.  
But Go also can do the same using [goplay](https://github.com/kless/goplay).


## Installation

	go get github.com/kless/shout


## License

The source files are distributed under the [Mozilla Public License, version 2.0](http://mozilla.org/MPL/2.0/),
unless otherwise noted.  
Please read the [FAQ](http://www.mozilla.org/MPL/2.0/FAQ.html)
if you have further questions regarding the license.

* * *
*Generated by [Gowizard](https://github.com/kless/wizard)*
