=== Upload Quota per User ===

Contributors: cristian.sarov
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=SF4HKR2UHFZXN
Tags: attachment limit, 
Requires at least: 2.8
Tested up to: 3.8
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Limits the total space a user can use uploading files, except selected roles.

== Description ==

For sites that are more than single-user blogs, this simple plugin sets a limited upload quota for users, except selected roles and capabilities.

= Features: =

* Set the limit for total upload quota. (applies to all files: images, .rar, .pdf, etc)
* If the upload quota exceeds, the file is prevented from uploading and the user gets an error message.
* On the Media Library page, the user see the space it uses in size and percentage.
* Certain User Roles or Capabilities can be added to not be affected by this restriction.

If you have any idea that can improve this plugin, or some bug, don't hesitate to write me on the support tab.

== Installation ==

1. Download, Install, and Activate the Upload Quota per User plugin.
2. On the Media menu, select Upload Quota and choose your settings.
3. You are finished setting the plugin, now your users have upload quota restriction.

== Frequently Asked Questions ==

= When activating the plugin how does fill the database? =

At plugin activation, it searches for every attachment, detects its size, and adds to its author.

= If an Admin deletes another user's media file, does the quota apply? =

Yes, whenever an attachment is deleted by the owner or administrator, the author of that attachment is affected.

= Where is this information stored? =

The settings on WP Settings API and the upload quota in the user_meta.

= Does this plugin delete all the data at deactivation? =

Yes, it does. It will not leave any trace in the database.

== Screenshots ==

1. The Upload Quota settings page.
2. The Media Library page with Used Space Notification.
3. The Upload Error on reaching the upload limit.

== Changelog ==

= 1.0 =
* Initial release

== Upgrade Notice ==

= 1.0 =
* none