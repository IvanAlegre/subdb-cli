CLI Subtitle downloader
=================

Download subtitles from the command line. Uses the api from http://thesubdb.com.

![demo](https://cloud.githubusercontent.com/assets/124599/7159049/73c7273e-e390-11e4-85b1-38c09b020fa2.gif)

Need a CLI for Pirate Bay? Try [kaizoku](https://github.com/arshad/kaizoku).

Installation
--------------

    $ npm install -g subdb-cli

Usage
--------------

Download subtitle:

    $ subdb download [file]
    $ subdb d [file]
    
Options
--------------

    -l, --language Language for the subtitle. Defaults to English.

Examples
--------------

    $ subdb download ./movie.avi
    $ subdb d ./movie.avi -l en
    
License
--------------

The MIT License (MIT)

Copyright (c) 2014 Arshad Chummun

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
