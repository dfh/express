# Express

Express is a Python _library_ to create _document processing pipelines_.

The main use case is to a) generate small(ish) static websites/blogs,
and b) slideshows and PDFs. It will do fast* incremental builds to
allow for near-realtime feedback. A live updater for web browsers will
be included, as a standalone program.

Express should be flexible enough to allow multiple kinds of input
formats, templating engines, and output formats. Initially, it will
support reST input, Mako templates and HTML output.

*) < 100 milliseconds on my mid-2011 MacBook Pro.

## Roadmap

Version 0.1: rendering a single reST document to a single HTML page
with Mako templating, with live updates in the browser. In other words
a workflow for authoring single HTML documents.

Version 0.2: multiple reST and LESS inputs, with HTML and CSS outputs.
In other words a workflow for creating static websites/blogs.

Version 0.3 will add incremental builds.
