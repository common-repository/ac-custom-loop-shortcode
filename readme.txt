=== AC Custom Loop Shortcode ===
Contributors: ambercouch
Donate link: http://ambercouch.co.uk/
Tags: shortcode, list post, list custom posts, timber, twig, custom post type
Requires at least: 4.6
Tested up to: 5.7
Stable tag: 1.5
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Shortcode to display posts in content areas.

== Description ==

A simple Wordpress plugin that creates Wordpress shortcode that will loop through posts, pages, or custom post types and display them on your website or blog. A typical use would be to show your latest post on your homepage.

== Installation ==

Use WordPress' Add New Plugin feature, searching "AC custom loop", or download the archive and:

1. Upload the plugin files to the `/wp-content/plugins/ac-wp-custom-loop` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Add the shortcode [ac_custom_loop] to the content area of any page, post or custom post type or to any widget that supports shortcode.
4. By default the shortcode will display your latest 4 post, you can use the 'type' and 'show' arguments to customise the type of post that are shown and how many eg. [ac_custom_loop type="page" show="3"] would show the last three published pages.


== Frequently Asked Questions ==

= Can I use my own template to display the looped posts? =

Yes you can! Simply copy loop-template.php from the plugin folder to the root of your theme folder and edit as needed.
You can also create a template for each post type such as loop-template-post.php or loop-template-page.php or loop-template-my-custom-post.php

== Screenshots ==

1. Add the code to any content area that accepts shortcode.
2. Posts, Pages or Custom post types are shown on the front end of your website.

== Upgrade Notice ==

= 1.5 =
Updated Timber support.

= 1.4.3 =
Fix release issues.

= 1.4.2 =
Fix template arguments to allow .php to be optional.

= 1.4.0 =
Updates to templates plus timber support and show posts using ids.

= 1.1.0 =
Updates to default template and post order.

= 0.1.1 =
Added user template function

= 0.0.1 =
Initial version

== Changelog ==

= 1.5 (2021-04-04) =
* Fix release issues.

= 1.4.3 (2019-12-06) =
* Fix release issues.

= 1.4.2 (2019-12-24) =
* Fix shortcode argument issues.

= 1.4.1 (2019-12-06) =
* Fix release issues.

= 1.4.0 (2019-12-05) =
* Added ids param to shortcode.
* Added post type templates.
* Added Timber template integration

= 1.1.0 (2018-10-16) =
* Added optional excerpt to the default template.
* Added default post order (post = date, everything else = menu_order).

= 0.1.1 (2018-10-13) =
* Added function to override template with the users own template
* Added GPLv2 licence
* Fixed some typos

= 0.1.0 (2018-10-07) =
* Initial version on WP repository
