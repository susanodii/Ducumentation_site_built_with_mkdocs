#  MkDocs 
Project documentation with Markdown

---


## Overview

MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

---
**MkDocs is currently still in development.**

We're progressing quickly, but the documentation still needs filling in, and there are a few rough edges. The 1.0 release is planned to arrive in the next few months.

---

**<h6> Host Anywhere</h6>**
Builds completely static HTML sites that you can host on GitHub pages, Amazon S3, or anywhere else you choose.

**<h6>Great themes available</h6>**
There's a stack of good looking themes included by default. Choose from bootstrap, readthedocs, or any of the 12 bootswatch themes.

**<h6>Preview your site as you work</h6>**
The built-in devserver allows you to preview your documentation as you're writing it. It will even auto-reload whenever you save any changes, so all you need to do to see your latest edits is refresh your browser.

**<h6>Easy to customize</h6>**
Get your project documentation looking just the way you want it by customizing the theme.
## Installation

In order to install MkDocs you'll need Python installed on your system, as well as the Python package manager, pip. You can check if you have these already installed like so:

```
$ python --version
Python 2.7.2
$ pip --version
pip 1.5.2
```

## Getting started
Getting started is super easy.

## Adding pages
Go ahead and edit the doc/index.md document, and change the initial heading to MkLorum, then reload the site in your browser, and you should see the change take effect immediately.

Let's also add a second page to our documentation:
```
$ curl 'jaspervdj.be/lorem-markdownum/markdown.txt' > docs/about.md
```
## Theming our documentation
While we're here can also change the configuration file to alter how the documentation is displayed. Let's go ahead and change the theme. Edit the mkdocs.yml file to the following:
```
site_name: MkLorum
pages:
- Home: index.md
- About: about.md
theme: readthedocs
```

## Building the site

That's looking good. We're ready to deploy the first pass of our MkLorum documentation now. Let's build the documentation.
```
$ mkdocs build
```

## Deploying

The documentation site that we've just built only uses static files so you'll be able to host it from pretty much anywhere. GitHub project pages and Amazon S3 are good hosting options. Upload the contents of the entire site directory to wherever you're hosting your website from and you're done. For specific instructions for a number of common hosts, see the Deploying your Docs page.
## Getting help
To get help with MkDocs, please use the discussion group, GitHub issues or the MkDocs IRC channel #mkdocs on freenode.

