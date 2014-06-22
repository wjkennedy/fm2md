fm2md
=====

Freemind to Markdown Converter in Python.

This is a simple tool that converts a Freemind mind map to Markdown format.

I'm developing it to help speed up the development of e-books for publication on LeanPub. LeanPub converts Markdown copy into a fine-looking published e-book; LeanPub authors need to provide their copy in Markdown format.

I've used mind maps for outlining over many years. Freemind is an excellent open source implementation that makes is easy to develop and reshape the text of an article or book, and I use it every day.

It's possible, but tedious, to take a Freemind mind map and manually create the contents in Markdown. Since Freemind stores mindmaps in a simple XML format, I though it would be straightforward to write a converter that takes a .mm file and generates the Markdown files you need to publish on LeanPub.

fm2leanpub is not finished, but it has enough features to be usable.

You can see an example of its use in the convert-map-to-blog script. It currently writes to standard output, so you will need to pipe the result to a file.


