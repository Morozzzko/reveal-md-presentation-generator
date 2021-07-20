# Reveal presentation generator

This is a generator for reveal.js based presentations.

It uses reveal-md, since I like it better than plain HTML.

## Usage

Run `make new` to generate new presentation. It'll prompt for a slug (directory name) for your presentation and create whatever needs to be created.

Inside the directories you'll find basic setup: `index.md` with the pre-configured presentation, `package.json` and a `Makefile`.

Use `make present` to run presentation locally, and use `make build-pdf` to render it as a pdf.

I have published the template to make it available to anyone who ever needs it. 

However, since I'm making it for my private presentations, I will rarely publish any updates to the generator here. All development will be in a private repository.

Feel free to contact me via Twitter, email or issues to ask for a newer version of a template. You can find my contact details in the profile.

## License

Copyright 2021 Igor S. Morozov

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
