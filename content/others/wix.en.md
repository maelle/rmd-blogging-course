---
title: Wix, Squarespace?
menuTitle: Wix &co
weight: 200
---

What about other services for building websites like Wix?

First, be careful you can export your content safely and easily before you commit to a website service.

Now for being able to use a workflow like the one we introduced with [`goodpress` for WordPress](https://github.com/maelle/goodpress/) you need

* the service to provide an API for publishing new posts and managing media (listing, deleting, uploading);

* to know what format the R Markdown output should have.

Then you'd need to write a script/package around that, using HTTP packages, rmarkdown, Pandoc, etc.

OR you could figure out what R Markdown output format to use and copy-paste to the post editor, and upload media by hand + tweak references to media path in the output.