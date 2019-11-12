# Better RSpec

Better RSpec syntax highlighting, with matchers for v3. Also includes implementation/spec toggling command.

## Installation

### Setup Package Control Repository

1. Follow the instructions from https://sublime.fnando.com.
2. Open the command pallete, run “Package Control: Install Package“, then search for “Better RSpec“.

### Git Clone

Clone this repository into the Sublime Text “Packages” directory, which is located where ever the “Preferences” -> “Browse Packages” option in sublime takes you.

## Toggling between implementation/spec

The default binding is `super-period`.

```json
{
  "keys": ["super+period"],
  "command": "rspec_toggle"
}
```

You can change it to whatever you by adding the following snippet to your Keybindings file.

```json
{
  "keys": ["ctrl+alt+down"],
  "command": "rspec_toggle"
}
```

## Syntax Detection

The best way of setting the syntax automatically is using the [ApplySyntax](https://sublime.wbond.net/packages/ApplySyntax) package. Just install it and you're done!

## License

The MIT License (MIT)

Copyright (c) 2014 Nando Vieira

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
