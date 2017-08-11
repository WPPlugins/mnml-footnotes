=== MNML Footnotes ===
Contributors: maurobringolf
Tags: footnotes, blogging, read, bibliography, footnote, formatting, notes, post, publishing, shortcode
Requires at least: 3.0
Tested up to: 4.8
Stable tag: 0.1.2
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple auto-listed footnotes for posts.

== Description ==

This plugin gives you a shortcode to make numbered references to footnotes, directly from your post content. Footnotes are listed and enumerated automatically at the end of your post
content, reusing all existing styles of your site. All references become anchor links guiding the user to the footnote section of the post.

We would love to hear and discuss your feedback in a [review](https://wordpress.org/support/plugin/mnml-footnotes/reviews/). If you want to report a bug or have a feature request, please do so via the [GitHub repository](https://github.com/maurobringolf/mnml-footnotes).

== Usage ==

To make a new footnote reference in your content you can use the shortcode **mnml_footnote** in the following way:

*This is your regular post content and the shortcode by this plugin looks like this [mnml_footnote] Easy, right? [/mnml_footnote]*

Everything inside the shortcode will be moved into a footnote and replaced by a numbered reference link to it. In this example the footnote content would be *"Easy, right?"*.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/mnml-footnotes` directory, or install the plugin through the WordPress plugins screen directly.

1. Activate the plugin through the **Plugins** area in WordPress.

1. Start using the shortcode `[mnml_footnote]Your footnote reference here.[/mnml_footnote]` within your post content.

1. Optionally, you can go to **Settings->Writing** and add a title for your footnotes sections on posts.

== Screenshots ==
1. Examples of footnote references taken from [maurobringolf.ch](https://maurobringolf.ch).

== Changelog ==

= v0.1.2 =
* A sketch of another shortcode was removed in favor of simplicity for now. Nothing changes though, the shortcode for
footnote references works exactly the same way as before.

= v0.1.1 =
* The plugin was renamed to MNML Footnotes.
* A bug concerning repeated footnotes referencing the same text has been fixed ( #3 ).
* Whitespace at the beginning and end of footnote content is now trimmed away.

= v0.1.0 =
* Footnotes that only contain a link will now automatically convert into anchor tags with target="_blank".
* The few words by this plugin on the settings page are now translatable. A `.pot` file for translations is also included inside the `/lang` directory.

= v0.0.1 =
Initial version.
