<h1>Writing your docs</h1>
---
File layout
Your documentation source should be written as regular Markdown files (see Writing with Markdown below), and placed in the documentation directory. By default, this directory will be named docs and will exist at the top level of your project, alongside the mkdocs.yml configuration file.

The simplest project you can create will look something like this:
```
mkdocs.yml
docs/
    index.md
```

By convention your project homepage should be named index.md (see Index pages below for details). Any of the following file extensions may be used for your Markdown source files: markdown, mdown, mkdn, mkd, md. All Markdown files included in your documentation directory will be rendered in the built site regardless of any settings.