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

How to build
------------

Download the KDE 4.8 kdepim directory (e.g. by cloning the KDE/4.8 branch
from https://projects.kde.org/projects/kde/kdepim/repository),
then replace/merge the akregator subdir with this project.

