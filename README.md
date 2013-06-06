# The Ultimate Sublime Text 2 JS Snippets

> Sublime Text 2 JavaScript snippets for commonly used functions and design patterns.

## Installation

### Sublime Text 2 - Package Control

TODO

### Mac OS X

    git clone git://github.com/ekryski/ultimate-js-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/JavaScript/ultimate-js-snippets

### Linux

    git clone git://github.com/ekryski/ultimate-js-snippets.git ~/.config/sublime-text-2/Packages/JavaScript/ultimate-js-snippets

### Windows

    git clone git://github.com/ekryski/ultimate-js-snippets.git %userprofile%\AppData\Roaming\Sublime Text 2\Packages\JavaScript\ulitmate-js-snippets


## Snippets

### JS Basics

* `for` - For Loop
* `do` - Do While Loop
* `fori` - For In Loop
* `fn` - Function
* `if` - If Statement
* `ifel` - If Else Statement
* `ins` - Inspect Object
* `sti` - Set Interval
* `log` - Console Log
* `proto` - Prototype Function
* `rand` - Random Number
* `us` - Use Strict
* `switch` - Switch Statement
* `sto` - Set Timeout

### JS Design Patterns

#### AMD

* `amd:def` - AMD Define
* `amd:req` - AMD Require
* `amd:conf` - RequireJS AMD Config
* `amd:single` - AMD Singleton

#### CommonJS

* `exp` - Exports
* `mexp` - Exports Module
* `req` - Require Module

#### Vanilla

* `v:class` - Classical Style Pattern
* `v:extend` - Extends Classical Style Pattern
* `v:literal` - Object Literal Module Pattern
* `v:proto` - Prototype Pattern


#### jQuery

* `$:plugin` - jQuery Plugin

### JS Testing ([ChaiJS](http://chaijs.com))

#### BDD

* `afta` - Asynchronous After
* `afts` - Synchronous After
* `befa` - Asynchronous Before
* `befs` - Synchronous Before
* `desc` - Describe
* `ita` - Asynchronous It
* `its` - Synchronous It

#### TDD

* `aeql` - Assert Equal
* `aneql` - Assert Not Equal
* `afail` - Assert Fail
* `afalse` - Assert False
* `atrue` - Assert True
* `aok` - Assert OK

### Backbone

#### AMD

* `bb:amd:c` - Backbone AMD Collection
* `bb:amd:m` - Backbone AMD Model
* `bb:amd:v` - Backbone AMD View
* `bb:amd:t` - Backbone AMD View with Template

#### Vanilla

TODO

### Underscore

TODO

## Credits

Some of these snippets are blatantly ripped off from the following fine individuals, so big ups goes to them as well:

* [Olivier Wietrich](https://github.com/bredele/bredele-sublime-snippets)
* [JP Richardson](https://github.com/jprichardson/sublime-js-snippets)
* [Sacha Schmid](https://github.com/RadLikeWhoa/JS-Snippets)


Design pattern snippets are adapted from Addy Osmani's [Essential JavaScript Design Patters](http://addyosmani.com/resources/essentialjsdesignpatterns/book/)

## License

Copyright 2013 Eric Kryski

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