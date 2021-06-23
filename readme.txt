=== Attachment URL Version ===
Contributors: ott
Tags: attachment, cache
Requires at least: 4.5
Tested up to: 5.7
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Adds the version number of attachments to their URL.

== Description ==

By default, attachments do not have a version query parameter, like, for example JavaScript have. This plugins adds version numbers to the query strings of attachments.

Version numbers are useful for caching. If an attachment changes, its version number and, therefore, its URL changes. This allows for the attachment to be cached for an extended period of time or indefintely, for example, with the directive "immutable" of the Cache-Control header.

== Changelog ==

= 1.0.0 =
* Initial release.
