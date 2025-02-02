=== Site-settings ===
Contributors: coderstime,lincolndu
Tags: Theme Basic settings, site settings, Theme settings, Site Social links
Requires at least: 4.9 or higher
Tested up to: 6.1
Requires PHP: 5.6
License: GPLv2 (or later)
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html
Stable tag: 1.1.1


Site-settings is the ultimate plugin for making all the necessary changes in the custom fields of a website. 

== Description ==

Site-settings is an official plugin maintained by the Coderstime team that adds an extra feature on the "Settings" option on the admin dashboard. It makes it possible to use plugins that extend that screen, add clean meta boxes.

Site Settings is an official Coderstime plugin, and will be fully supported and maintained until at least 2022, or as long as is necessary.

At a glance, this plugin adds the following:

Administrators can make the default changes for all users. The form includes the change in the site's logo, title, tagline, email, phone, address, copyrighted text along with the change in the social media links that are to be posted in the website.
When allowed, the plugin will ask for information to change and once the changes are submitted, there will be a confirmation box to alert the admin. Only admin will have the privilege to make all the necessary changes.
Each post opens in the last editor used regardless of who edited it last. This is important for maintaining a consistent experience when editing content.

By default, this plugin hides all functionality available in the new block editor (“Gutenberg”).

== Installation ==

For installation, it is quite easy. Anyone can install it from the the plugin repository and afterwards can be found in the install new plugin section. Once installed, it will require activation from the admin. Later, the plugin form can be found in the settings option as Site settings.


== Usage ==

to get site Logo url just use this shortcode

`
	[ss_option size="full"]site_logo[/ss_option]
`

to show site name just use this shortcode

`
	[ss_option]blogname[/ss_option]
`

to show site Description just use this shortcode

`
	[ss_option]blogdescription[/ss_option]
`

to show site Email just use this shortcode

`
	[ss_option]site_email[/ss_option]
`

to show site Phone just use this shortcode

`
	[ss_option]site_phone[/ss_option]
`

to show site Address just use this shortcode

`
	[ss_option]site_address[/ss_option]
`

to show Site Tags just use this shortcode

`
	[ss_option]site_tags[/ss_option]
`

to show Site Tags with tag link just use this shortcode

`
	[ss_option link="true"]site_tags[/ss_option]
`

to show Site Facebook link just use this shortcode

`
	[ss_option]site_facebook[/ss_option]
`

to show Site Twitter link just use this shortcode

`
	[ss_option]site_twitter[/ss_option]
`

to show Site Instagram link just use this shortcode

`
	[ss_option]site_instagram[/ss_option]
`


to show Site Youtube link just use this shortcode

`
	[ss_option]site_youtube[/ss_option]
`


== Don't Know Shortcode ? ==

[Wordpress Shortcode](https://developer.wordpress.org/reference/functions/do_shortcode/)


== Frequently Asked Questions ==

When activated this plugin will allow the admin to make changes in the custom fields.
These settings can be changed at the Settings => Site-Settings.

== Screenshots ==
1. Site Settings Panel
2. Site Settings Menu


== Changelog ==

= 1.1.0 =
* product_tags change to site_tags
* add Post tags with product tags
* show tag list with tag link
* fix bug
* activate plugin with default data
* Documentation and community support tab

= 1.0.1 =
* Default Logo 
* Shortcode system upgrad
* select2 file location change

= 1.0.0 =
* Initial release.
