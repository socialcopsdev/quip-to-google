# Quip Mass Exporter

## What is this?
The popular [Quip app](https://quip.com/) is great for note-taking and documents, but only allows you to export your documents one by one. This tool hooks into their API and allows you to export all of your documents at once into Docx.

## Installation
1. `brew update && brew install node`
2. `brew install yarn`

## Use
1. Generate a personal access token for the Quip API here: https://quip.com/api/personal-token
2. Open terminal.
3. Clone the repo: `git clone git@github.com:socialcopsdev/quip-to-google.git`
4. Run `cd quip-to-google`
5. Run `npm install`
6. Run `node index.js '<quip-token>'`
7. This will dump all your documents in .docx format into an `output/` folder
8. You can now directly import output folder to your Google Drive

## License
Copyright 2017 Ben Makuh

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
