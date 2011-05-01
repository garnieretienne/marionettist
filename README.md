# About 'marionettist'

This script is attended to fast deploy a working puppet node, for testing or development purpose. It's a fast install and run script.  

Last post entry:   
Last screencast:   

# Supported linux distributions

* Debian

Want to make this script usable in more distributions ? see 'Adapt it' section.

# Getting started

## Dependencies

* bash
* lsd_release
* sed
* wget

## Get the script

`wget https://github.com/garnieretienne/install_puppet/blob/master/marionetist`

## And use it

TODO: --help output

# Adapt it

## Get the last development version

TODO: git command to develop branch

...

## Some code conventions used in this script

* Step functions: master_step_*, agent_step_* or general_step_*
* Step functions: using case to define default or per distribution step
* Step functions: to echo use '>__your message', with '_' a space
* Step functions: use -0.5 indent space to comment your actions, better visibility

# License MIT

Marionettist - Fast install and run script for puppet, Copyright (C) 2011 Etienne Garnier <garnier.etienne@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
