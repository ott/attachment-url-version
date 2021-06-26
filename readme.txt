=== Attachment URL Version ===
Contributors: ott
Tags: attachment, cache
Requires at least: 4.5
Tested up to: 5.7
Requires PHP: 7.4
Stable tag: 1.0.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Adds the version number of attachments to their URL.

== Description ==

By default, attachments do not have a version query parameter, like, for example JavaScript files have. This plugins adds version numbers to the query strings of attachments.

Version numbers in query strings are useful for caching. If an attachment changes, its version number and, therefore, its URL changes. This allows for the attachment to be cached for an extended period of time or indefintely, for example, with the directive "immutable" of the Cache-Control header.

== Changelog ==

= 1.0.3 =
* Properly prepare the plugin for localization.

= 1.0.2 =
* Minor corrections in readme.txt.

= 1.0.1 =
* Change plugin URL to wordpress.org.

= 1.0.0 =
* Initial release.
