# jsmd
JS M.D. - Client side support for Markdown (based on [marked](https://github.com/chjj/marked/))

Browsers should support markdown in addition of all the HTML versions they support.

But they don't.

This quick'n'dirty hack allows you to write markdown files and generate html content on the client-side, on the fly.

Please open an issue or a pull request if you have bugs, suggestions or improvements.

Installation
============

0. **Place** the index.html file in the root of your website.
0. **Create** new files, containing your content, formatted in markdown.
0. **Name** those files after the name of each of your pages<sup>1</sup> (the internal links in your markdown), and add an `.md` extension to their name<sup>2</sup>.
0. **Add** some CSS style (optional).
0. **Edit/Add** HTML `<meta ... />` fields for SEO (optional).
0. **Profit**.

<sup>1</sup> *The default page (that corresponds to the link `/`) shall be named `index.md`.

<sup>2</sup> *Note that for each markdown link ending with `/`, a folder with the name of your link will be searched for and `index.md` file, instead of a file ending with `.md` placed at the root of your website*.
