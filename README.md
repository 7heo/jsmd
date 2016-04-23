# jsmd
JS M.D. - Client side support for Markdown (based on [marked](https://github.com/chjj/marked/))

Browsers should support markdown in addition of all the HTML versions they support.

But they don't.

This quick'n'dirty hack allows you to write markdown files and generate html content on the client-side, on the fly.

Please open an issue or a pull request if you have bugs, suggestions or improvements.

Installation
============

0. Place the index.html file in the root of your website.
0. Write your content in markdown, inner links are to be used without extensions, if links are ended with ```/```, **jsmd** will search for a folder having that link's name, and containing an ```index.md``` file (instead of a file named after that link's target, and having the ```.md``` extension).
0. Add some CSS style (optional).
0. Download the marked.js file from github (optional).
0. Profit.
