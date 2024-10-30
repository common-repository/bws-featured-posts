=== Featured Posts by BestWebSoft ===
Contributors: bestwebsoft
Donate link: https://bestwebsoft.com/donate/
Tags: add featured posts, display featured posts, featured, featured posts block, featured posts plugin, manage featured posts, mark page as featured, post,  faetured post, feachured post, free, free featured posts, mark page as featured
Requires at least: 3.9
Tested up to: 4.8
Stable tag: 1.0.2
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Add featured posts to WordPress website posts and widgets. Highlight important information.

== Description ==

Simple plugin which helps to add and manage featured posts on your WordPress website. Customize featured posts section appearance, change its position, choose any post and make it featured.

Highlight important information for your visitors!

https://www.youtube.com/watch?v=7Z5d1qZpwrM

= Features =

* Mark any post or page as a featured
* Use shortcode to add featured posts section
* Add featured posts to widget
* Choose featured posts position:
	* Before post
	* After post
	* Shortcode
* Set the number of posts to display
* Set featured posts:
	* Inner content width
	* Section width
* Customize featured posts color:
	* Section background
	* Text background
	* Section title
	* Description
	* Learn more link
* Changing featured posts with reloading
* Compatible with latest WordPress version
* Incredibly simple settings for fast setup without modifying code
* Detailed step-by-step documentation and videos

If you have a feature suggestion or idea you'd like to see in the plugin, we'd love to hear about it! [Suggest a Feature](https://support.bestwebsoft.com/hc/en-us/requests/new)

= Documentation & Videos =

* [[Doc] Installation](https://docs.google.com/document/d/1-hvn6WRvWnOqj5v5pLUk7Awyu87lq5B_dO-Tv-MC9JQ/)
* [[Video] Installation Instruction](https://www.youtube.com/watch?v=MlVrRIKSxhA)

= Help & Support =

Visit our Help Center if you have any questions, our friendly Support Team is happy to help — <https://support.bestwebsoft.com/>

= Translation =

* Russian (ru_RU)
* Ukrainian (uk)

Some of these translations are not complete. We are constantly adding new features which should be translated. If you would like to create your own language pack or update the existing one, you can send [the text of PO and MO files](https://codex.wordpress.org/Translating_WordPress) to [BestWebSoft](https://support.bestwebsoft.com/hc/en-us/requests/new) and we'll add it to the plugin. You can download the latest version of the program for work with PO and MO [files Poedit](https://www.poedit.net/download.php).

= Recommended Plugins =

* [Updater](https://bestwebsoft.com/products/wordpress/plugins/updater/?k=6718ea1981e24281e2f7e1a95b64dd14) - Automatically check and update WordPress website core with all installed plugins and themes to the latest versions.
* [Relevant – Related, Featured, Latest, and Popular Posts](https://bestwebsoft.com/products/wordpress/plugins/related-posts/) - Add related posts to WordPress posts or widgets. Link your readers to relevant content.

== Installation ==

1. Upload the `bws-featured-posts` folder to `/wp-content/plugins/` directory.
2. Activate the plugin using the 'Plugins' menu in your WordPress admin panel.
3. You can adjust the necessary settings using your WordPress admin panel in "BWS Panel" > "Featured Posts".

[View a Step-by-step Instruction on Featured Posts Installation](https://docs.google.com/document/d/1-hvn6WRvWnOqj5v5pLUk7Awyu87lq5B_dO-Tv-MC9JQ/)

https://www.youtube.com/watch?v=MlVrRIKSxhA

== Frequently Asked Questions ==

= How can I add a Featured Post to my website? =

If you would like to add Featured Posts to your page or post, select the posts to be displayed (on the page/post editing page, in Featured Post block, please mark "Display this post in the Featured Post block?").

There are several ways to add the block, please use one of them: 
1. Enable block display Before the Post and/or After the Post on the plugin settings page. 
2. Copy and paste this shortcode into your post or page: [bws_featured_post].
3. Copy and paste this code to the necessary place in your theme:

`<?php if ( has_action( 'ftrdpsts_featured_posts' ) ) { do_action( 'ftrdpsts_featured_posts' ); } ?>`

= I have installed the plugin and went through the above-mentioned steps to add a block, yet the block is not displayed. Why? =

Please select the necessary posts to be displayed (on the page/post editing page, in Featured Post block, please mark "Display this post in the Featured Post block?").

= How can I customize the block? =

On the plugin settings page, you can change block color, text block color, title color, text color and "Learn more" link color. 
Also, you can select the width of the entire block and the text block.

= I have some problems with the plugin's work. What Information should I provide to receive proper support? =

Please make sure that the problem hasn't been discussed yet on our forum (<https://support.bestwebsoft.com>). If no, please provide the following data along with your problem's description:

- The link to the page where the problem occurs
- The name of the plugin and its version. If you are using a pro version - your order number.
- The version of your WordPress installation
- Copy and paste into the message your system status report. Please read more here: [Instruction on System Status](https://docs.google.com/document/d/1Wi2X8RdRGXk9kMszQy1xItJrpN0ncXgioH935MaBKtc/)

== Screenshots ==

1. Featured Posts block display with Custom plugin settings (default theme).
2. Featured Posts block display with Custom plugin settings (BestWebSoft theme).
3. Featured Posts settings.

== Changelog ==

= V1.0.2 - 19.06.2017 =
* Update : Featured Posts plugin is now a part of Relevant – Related, Featured, Latest, and Popular Posts plugin. It will be no longer supported (updates will be unavailable) starting from July 2017. Install [Relevant plugin](https://wordpress.org/plugins/relevant/) now to automatically apply your current settings and get new amazing features.

= V1.0.1 - 17.04.2017 =
* Bugfix : Multiple Cross-Site Scripting (XSS) vulnerability was fixed.

= V1.0.0 - 12.10.2016 =
* Update : BWS plugins section is updated

= V0.9 - 26.08.2016 =
* NEW : Ability to select the number of displayed posts for Featured Posts block has been added.

= V0.8 - 11.07.2016 =
* Bugfix : Bug with displaying Featured Posts in the secondary query has been fixed.

= V0.7 - 18.04.2016 =
* NEW : Ability to add custom styles.

= V0.6 - 09.12.2015 =
* Bugfix : The bug with plugin menu duplicating was fixed.

= V0.5 - 20.10.2015 =
* NEW : A button for Featured Posts shortcode inserting to the content was added.
* NEW : We added ability to restore settings to defaults.
* Update : Textdomain was changed.

= V0.4 - 05.06.2015 =
* Update : Input maxlength and input validation is added.
* Bugfix : We fixed block width settings.
* Update : We updated all functionality for wordpress 4.2.2.

= V0.3 - 29.04.2015 =
* Update : We updated all functionality for wordpress 4.2.1.

= V0.2 - 09.02.2015 =
* Bugfix : Content display was fixed.

= V0.1 - 26.01.2015 =
* Bugfix : The code refactoring was performed.
* NEW : Css-style was added.

== Upgrade Notice ==

= V1.0.2 =
Featured Posts plugin is no longer supported.

= V1.0.1 =
* Bugs fixed.

= V1.0.0 =
* Plugin optimization completed.

= V0.9 =
* Functionality expanded

= V0.8 =
Bug with displaying Featured Posts in the secondary query has been fixed.

= V0.7 =
Ability to add custom styles.

= V0.6 =
The bug with plugin menu duplicating was fixed.

= V0.5 =
A button for Featured Posts shortcode inserting to the content was added. We added ability to restore settings to defaults. Textdomain was changed.

= V0.4 =
Input maxlength and input validation is added. We fixed block width settings. We updated all functionality for wordpress 4.2.2. BWS Panel section was updated.

= V0.3 =
We updated all functionality for wordpress 4.2.1.

= V0.2 =
Content display was fixed.

= V0.1 =
The code refactoring. Css-style was added.