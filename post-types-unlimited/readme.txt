=== Post Types Unlimited ===
Contributors: WPExplorer
Donate link: https://www.wpexplorer.com/donate/
Tags: custom post types, post types, types, cpt, taxonomies
Requires at least: 5.2.0
Requires PHP: 7.4
Tested up to: 6.6
Stable Tag: 1.2.3
License: GPL v2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Create unlimited custom post types and custom taxonomies.

== Description ==
Post Types Unlimited is an easy way to add **custom post types** and **custom taxonomies** to your WordPress site (the right way). The plugin works with any theme and is easily translatable. With Post Types Unlimited you can:

* Create custom post types.
* Create custom taxonomies.

Post Types Unlimited makes use of core WordPress functionality for the admin screens and post type, taxonomy registration. This means the plugin is fast, slim and uses the familiar Wordpress UI.

Additionally you won't find any upsell or advertisements in the plugin because there isn't a "Pro" version. It's the perfect plugin for adding post types and/or taxonomies to any site (including your client sites) without worrying about extra bloat or annoying ads.

The design of your post types and taxonomies created with the Post Types Unlimited plugin are controlled by your theme. The plugin doesn't do any hacking or advanced modifications to your templates and thus works great with ANY theme.

If you are using our amazing [Total WordPress Theme](https://totalwptheme.com/) you will have access to many extra settings that will give you full control over the display of your post types and taxonomies.

This plugin doesn't have any upsells, banners or other marketing strategies. This makes it perfect for use with any site, including client websites.

== Installation ==

1. Upload 'post-types-unlimited' to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to Post Types to add new custom post types
4. Go to Post Types > Taxonomies to add new custom taxonomies

== Frequently Asked Questions ==

= What does the plugin do? =
It adds a new tab in the WordPress admin panel called "Post Types" where you can add new custom post types or custom taxonomies to your site.

= Can I export my custom post types and taxonomies? =
Yes you can! The plugin actually uses a post type to register your custom types and taxonomies thus you can use the core WordPress exporter/import for this.

= Is there a premium version? =
Nope. This plugin includes everything you need to register custom post types and taxonomies.

= Can I add custom options for my theme? =
Yes! Post Types Unlimited is a great companion plugin for your theme. Here is the guide to [adding custom options to the post types unlimited plugin](https://www.wpexplorer.com/post-types-unlimited-custom-options/).

== Changelog ==

= 1.2.3 =
* Added new metabox field types for use with 3rd party integrations: page, taxonomy & image_size.
* Updated the readme.txt file to include a new FAQ on how to add custom options for your theme.
* Removed the not needed index.php file in plugin's root directory.

= 1.2.2 =
* Updated the tested up to version.
* Updated the conditional logic code for showing/hiding settings to support checkboxes.
* Updated various label and input placeholder strings.
* Fixed the search box in the post type icon selector.
* Removed the SASS file from production.

= 1.2 =
* Added over 50 more Dashicon choices for your post type icon.
* Updated UI to use a single metabox with tabs instead of multiple metaboxes.
* Updated the post type icon selector UI.
* Updated the code used to register metaboxes so it's better optimized.
* Updated the post type and taxonomy creation process so the name and label is automatically set when adding your title.
* Updated the "Tested up to" tag to version 6.3.

= 1.1 =
* Added new helper functions that return a list of registered post types or taxonomies to prevent extra database checks for 3rd party integrations.
* Updated the "Tested up to" tag to version 6.1.1
* Fixed post preview not working when enabling support for 'post-formats' for any given post type.

= 1.0.9 =
* Updated the "Tested up to" tag to version 6.0.2
* Removed duplicate "Menu Name" option for taxonomies.

= 1.0.8 =
* Added a new PTU_VERSION constant.

= 1.0.7 =
* Updated the tested up to version 6.0.1
* Updated the metabox class so you can pass a callback function name for select choices.

= 1.0.6 =
* Updated the "Tested up to" to version 5.9.3
* Updated the requires PHP version to 7.4
* Updated various code to use newer PHP methods.

= 1.0.5 =
* Added sanitization when saving post type names to allow underscores and dashes (passes through sanitize_key).

= 1.0.4 =
* Fixed Public and Publicly Queryable arguments not working for custom taxonomies.

= 1.0.3 =

* Fixed potential debug error in Metaboxes.php on line 158.
* Updated admin dashboard columns to display useful details.

= 1.0.2 =

* Improved Menu Icon selector.
* Updated Menu Icon Dashicons list to include new Dashicons added in WP 5.5.
* Improved meta field save function to allow 0 to be saved for text and number fields.
* Added ability to display placeholders for number fields.

= 1.0.1 =

* Fixed issue "With Front" option not working correctly.

= 1.0 =

* First official release