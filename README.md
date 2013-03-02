**NOTE: I no longer maintain this plugin**

# SuperLinks

SuperLinks is a WordPress plugin that replaces the standard Links sidebar widget. SuperLinks gives the site owner greater control over how links in the sidebar are displayed. For example, one can choose to display all links categories or only a single links category. Additionally, a site owner may have any number of SuperLinks widgets in the sidebar. It has been tested with WordPress 2.5, 2.5.1, 2.6, 2.6.3, 2.7, 2.8 and 3.5.1.

SuperLinks was inspired by the [LinkBlock](http://www.optera.net/projects/wordpress/linkblock/) plugin, which provided a very similar service. However, LinkBlock development stopped before WordPress 2.5, so SuperLinks was created to fill the void.

I hope you find SuperLinks useful on your own site!

## Installation

Follow these simple steps:

1. Remove all existing Links sidebar widgets (see FAQ for why)
1. Upload `superlinks.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Go to your widgets administration and add and cofigure SuperLinks widgets

## Frequently Asked Questions

* What happened to the standard Links widget?

> When SuperLinks registers itself, it unregisters the Links widget that comes installed with
WordPress by default. Don't worry though -- anything you could have done with the standard
Links widget can be done with SuperLinks.

## To-Do

Here’s a list of some things that would be nice to have in SuperLinks:

* Ability to override the link category title
* When showing all categories, option to set the category order (asc, desc)
* Configure link display order (asc, desc)
* Change the text in the draggable box
* More code cleanup

## Credits

Development of SuperLinks was greatly aided by reading the source of some existing plugins. They are:

* Lorna Timbah’s "[Top Commentators Widget](http://webgrrrl.net/archives/my-top-commentators-widget-quick-dirty.htm)"
* The original [LinkBlock](http://www.optera.net/projects/wordpress/linkblock/) widget
* The stock WordPress widgets found in widgets.php
* Thanks to the developers of those plugins for the help their code provided!

## Version History

Version 0.1

> The initial release of SuperLinks
