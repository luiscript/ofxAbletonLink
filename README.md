# ofxAbletonLink

[Ableton Link](https://www.ableton.com/ja/link/) addon for [openFrameowkrs](http://openframeworks.cc)

## Test

* OSX Yosemite 10.10.5
* Xcode 7.2
* oF0.9.6 osx release

## Setup

```
git clone git@github.com:2bbb/ofxAbletonLink.git
cd ofxAbletonLink
git submodule update --init --recursive
```

### if you don't use ProjectGenerator

* add header search path
  * ofxAbletonLink/libs/link/include
  * ofxAbletonLink/libs/link/modules/asio-standalone/asio/include
  * ofxAbletonLink/libs/link/modules/catch/include
* add project
  * ofxAbletonLink/src/ofxAbletonLink.h
  * __!!! DON'T add other files to project__

## Update histor

### 2016/11/28 ver 0.0.1

## License

MIT License.

## Dependencies license

### [Ableton Link](https://www.ableton.com/link/)

* [Ableton/link](https://github.com/Ableton/link)

GNU GPL v2.0

```
Copyright 2016, Ableton AG, Berlin. All rights reserved.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

If you would like to incorporate Link into a proprietary software application,
please contact <link-devs@ableton.com>.
```

### [asio](http://think-async.com/Asio/AsioStandalone)

### [Catch](https://github.com/philsquared/Catch)

* [chriskohlhoff/asio](https://github.com/chriskohlhoff/asio)
* [philsquared/Catch](https://github.com/philsquared/Catch)

boost v1.0

```
Boost Software License - Version 1.0 - August 17th, 2003

Permission is hereby granted, free of charge, to any person or organization
obtaining a copy of the software and accompanying documentation covered by
this license (the "Software") to use, reproduce, display, distribute,
execute, and transmit the Software, and to prepare derivative works of the
Software, and to permit third-parties to whom the Software is furnished to
do so, all subject to the following:

The copyright notices in the Software and this entire statement, including
the above license grant, this restriction and the following disclaimer,
must be included in all copies of the Software, in whole or in part, and
all derivative works of the Software, unless such copies or derivative
works are solely in the form of machine-executable object code generated by
a source language processor.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT
SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE SOFTWARE BE LIABLE
FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```

## Author

* ISHII 2bit [bufferRenaiss co., ltd.]
* ishii[at]buffer-renaiss.com

## Contributor

* [hiroMTB](https://github.com/hiromtb)
