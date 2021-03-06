=== wp-permamod ===
Contributors: pierreprinetti
Tags: permalink, anchor
Requires at least: 2.7
Tested up to: 5.2.2
Stable tag: 0.3.2
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Very simple plugin that adds an anchor to page and post permalinks,
which can point to an existant anchor in your template.

== Description ==

Set your anchor name in the options page.

Typical use case: a big picture in the header you don't want people
to be bothered with every time they click on an internal link. But
you still want that beautiful picture to be there.

Feel free to contribute:  
github.com/pierreprinetti/wp-permamod

== Installation ==

1. Upload `wp-permamod.php` to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

OR

Just use the automated function from inside your Wordpress dashboard.

== Changelog ==

= 0.3.2 =
* Update the latest tested Wordpress version

= 0.3 =
* Revert to 0.1, working on unstable features in a separate branch

= 0.2.1 =
* Small fix to handle the case you've not set an anchor name.

= 0.2 =
* Now asks you for a custom anchor name

= 0.1 =
* Trivial, but still works.
