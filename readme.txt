=== Get Filesize Shortcode ===
Contributors: ikaring
Donate link: http://example.com/
Tags: shortcode, filesize, pdf
Requires at least: 3.0.1
Tested up to: 4.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

"Get Filesize Shortcode" is a simple shortcode to get filesize of a file( eg. PDF, JPG, PNG ... ).

== Description ==

"Get Filesize Shortcode" is a simple shortcode to get filesize of a file( eg. PDF, JPG, PNG ... ) with a human readable format, using the largest unit the bytes will fit into.

#### Usage

Put **`[filesize]http:yoursite.com/path/to/file.pdf[/filesize]`** anywhere in a post.

Alse you can place **`<?php echo do_shortcode('[filesize]http:yoursite.com/path/to/file.pdf[/filesize]'); ?>`** in your templates.

#### Note

*   File must be in your server
*   With files larger than 2MB, it might return different number due to the spec of filesize function of PHP.

== Installation ==

1. Upload `get-filesize-shortcode` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

None yet.

== Screenshots ==

None.

== Upgrade Notice ==

None.

== Changelog ==

= 1.0 =
