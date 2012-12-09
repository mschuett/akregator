akregator
=========

some hacks on KDE Akregator

Pagination
----------

First step is to add a simple pagination.

The Settings -- Appearance gets a new option for the number of items per page.
The "Combined View" will only show this number of articles on one page.

Additionally there is a new "Mark Page as Read" action to add to the Toolbar.

Note: There is no way to turn or skip pages. So far the only use case is to
go through the feed by reading a page and then marking it read.

Mosaic View
-----------

Second step: add a tiled or tabular view to quickly browse image feeds.

[Here is a screenshot.](http://mschuette.name/wp/wp-upload/akregator_mosaic_pagination.png)

How to build
------------

Download the KDE 4.8 kdepim directory (e.g. by cloning the KDE/4.8 branch
from https://projects.kde.org/projects/kde/kdepim/repository),
then replace/merge the akregator subdir with this project.

Note of Caution
---------------

This is just a small hack on a "works for me" level.
The mosaic HTML design is quite ugly and not suitable for anything except
single-picture-posts.

Furthermore I have never programmed with Qt/KDE before, so all changes
may contain cargo cult programming.

