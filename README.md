=== Notification Email Plugin ===
Tags: email, notification, post publish, admin
Requires at least: 5.0
Tested up to: 6.4
Stable tag: 1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Sends a notification email to the admin whenever a new post is published.

== Description ==
The Notification Email Plugin is a lightweight WordPress plugin that automatically sends an email notification to the site admin whenever a new post is published. 

Features:
* Sends email notifications on post publication.
* Includes the post title, content, and permalink in the email.
* Simple to set up and use.

== Installation ==
1. Download the plugin ZIP file or copy the single PHP file.
2. Upload the `notification-email-plugin.php` file to the `/wp-content/plugins/` directory.
3. Log in to your WordPress admin dashboard.
4. Navigate to **Plugins > Installed Plugins**.
5. Activate the "Notification Email Plugin."

== Usage ==
1. Once activated, the plugin will automatically send an email notification to the admin email address configured in your WordPress settings whenever a new post is published.
2. No additional configuration is required.

== Frequently Asked Questions ==

= Can I customize the email content? =
Yes, you can edit the plugin file and modify the `send_notification_email` function to customize the email subject and message.

= Does it support other post types? =
Currently, the plugin only supports standard posts. You can modify the code to add support for custom post types if needed.

== Changelog ==

= 1.0 =
* Initial release.

== License ==
This plugin is licensed under the GPLv2 or later. For more information, see https://www.gnu.org/licenses/gpl-2.0.html.
