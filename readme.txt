=== Instant Comment Validation ===
Contributors: mkrdip 
Tags: comment validation, wordpress comment validation plugin 
Requires at least: 3.6  
Tested up to: 3.9.1 
Stable tag: trunk 
License: GPLv2 or later 
License URI: http://www.gnu.org/licenses/gpl-2.0.html 

Add a instant validator for WordPress comment form, instead of sending users to default error page.

== Description ==

WordPress deafult comment error page sucks? Its just showing an error message like "please fill out required fields" and nothing else? Trying to get rid out of this & keep users in that page. Then “Instant Comment Validation” is for you. This plugin adds validation to the comment form. When a user submits the form and something is missing, an appropiate message is displayed and individual fields are highlighted. 

That's it, no configuration needed, just install & enjoy! 

= Credit =
This plugin is using [jQuery Validation plugin](http://jqueryvalidation.org/) library.

== Installation ==

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don’t need to leave your web browser. To do an automatic install of Instant Comment Validation, log in to your WordPress dashboard, navigate to the Plugins menu and click Add New.

In the search field type “Instant Comment Validation” and click Search Plugins. Once you’ve found plugin, you can install it by simply clicking “Install Now”.

= Manual installation =
1. Extract the zip file 
2. Upload the `instant-comment-validation` folder to `/wp-content/plugins/`
3) Activate the plugin through the 'Plugins' menu in WordPress


== Frequently Asked Questions ==

= The plugin files load even if the comments are closed? =
Answer: No, then plugin assests do not load unnecessarily. If your post in single & comments are open then then plugin loades it files.

== Screenshots ==

1. Validation error message showing in Twenty Fourteen Theme
2. Validation error message showing in Twenty Thirteen Theme
3. Validation error message showing in Twenty Twelve Theme

== Changelog ==

= 1.0 =
* Initial release

== Upgrade Notice ==

Nothing here
