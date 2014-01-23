rss-rebuilder
=============

Python utility to rebuild RSS files with relevant content

Takes a source RSS file and, for each item, extracts content from the linked
URL according to a CSS selector.

Requirements
------------

* Python 2.x
* argparse (included in Python starting from 2.7)
* feedparser
* requests
* Beautiful Soup 4

