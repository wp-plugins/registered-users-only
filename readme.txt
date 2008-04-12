=== Registered Users Only ===
Contributors: Viper007Bond
Donate link: http://www.viper007bond.com/donate/
Tags: restriction, registered only, registration
Requires at least: 2.0
Stable tag: trunk

Forces all users to login before being able to view your site. Features an options page for configuration.

== Description ==

Have a private blog that you only want your friends or family to read? Then this plugin is for you. It will redirect all users who aren't logged in to the login form where they are shown a user-friendly message.

This plugin also features a configuration page where you can allow guests to access your feeds, post pingbacks and trackbacks, or for you to access the XML-RPC script from an external blog posting program.

Unlike other registered users only scripts, you can't get around this one by just visiting `index.php/wp-login.php` nor does it break `wp-cron.php` or anything else.

== Installation ==

###Updgrading From A Previous Version###

To upgrade from a previous version of this plugin, delete the entire folder and files from the previous version of the plugin and then follow the installation instructions below.

###Installing The Plugin###

Extract all files from the ZIP file, making sure to keep the file structure intact, and then upload it to `/wp-content/plugins/`.

This should result in the following file structure:

`- wp-content
    - plugins
        - registered-users-only
            | registered-users-only.php
            | readme.txt`

Then just visit your admin area and activate the plugin.

**See Also:** ["Installing Plugins" article on the WP Codex](http://codex.wordpress.org/Managing_Plugins#Installing_Plugins)

###Using The Plugin###

Sit back and relax! You can visit the configurations page at Settings -> Registered Only to optionally set some preferences.

== Screenshots ==

1. The login form now with the error message
2. The plugin's options page

== ChangeLog ==

**Version 1.0.0**

* Initial release.