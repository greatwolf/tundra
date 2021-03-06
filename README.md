
Tundra, a build system
=============================================================================

Tundra is a high-performance code build system designed to give the best
possible incremental build times even for very large software projects.

Tundra is portable and works on

  - Mac OSX (10.6-10.7 tested, but most any version should work)
  - Linux
  - FreeBSD
  - Windows (XP and later, 32/64 bit native)

Porting to UNIX-like platforms will be very easy, porting to other platforms
will take a little bit of work in a few well-defined places.

See doc/manual.asciidoc for more detailed usage information.

License and Copyright
-----------------------------------------------------------------------------

Tundra is Copyright 2010-2012 Andreas Fredriksson.

Tundra is made available under the GNU GPL. See the file COPYING for the
complete license text.

Tundra uses Lua. See below for Lua's licensing terms which are compatible with
those of the GNU GPL.

Tundra includes a public domain MD5 algorithm.

Tundra includes a public domain Lua Debugger, see below.

Lua
-----------------------------------------------------------------------------

Copyright (c) 1994-2008 Lua.org, PUC-Rio.
Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

MD5
-----------------------------------------------------------------------------

Written by Solar Designer `<solar at openwall.com>` in 2001, and placed in the
public domain.  There's absolutely no warranty.

Lua Debugger
-----------------------------------------------------------------------------

Tundra includes an optional Lua CLI debugger which is public domain software
written by Dave Nichols.

The debugger was obtained from [luaforge.net](http://luaforge.net/projects/clidebugger/).
