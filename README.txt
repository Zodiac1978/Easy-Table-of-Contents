=== Easy Table of Contents ===
Contributors: magazine3
Donate link: https://magazine3.company/
Tags: table of contents, toc
Requires at least: 5.3
Tested up to: 6.0
Requires PHP: 5.6.20
Stable tag: 2.0.32
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Adds a user friendly and fully automatic way to create and display a table of contents generated from the page content.

== Description ==

A user friendly, featured focused [Easy Table of Contents](https://tocwp.com/) plugin which allows you to insert a table of contents into your posts, pages and custom post types.

[Home](https://tocwp.com/) | [Documentation](https://tocwp.com/docs/) | [Help](https://tocwp.com/contact/) | [Premium version Features](https://tocwp.com/pricing/)

### Features 
* Automatically generate a table of contents for your posts, pages and custom post types by parsing its contents for headers.
* Supports the `<!--nextpage-->` tag.
* Supports the Rank Math plugin.
* Works with the Classic Editor, Gutenberg, Divi, Elementor, WPBakery Page Builder and Visual Composer page editors.
* Optionally enable for pages and/or posts. Custom post types are supported, as long as their content is output with the `the_content()` template tag.
* Optionally auto insert the table of contents into the page, selectable by enabled post type.
* Provides many easy to understand options to configure when and where to insert the table of contents.
* Many options are available to configure how the inserted table of contents appears which include several builtin themes. If the supplied themes do no meet you needs, you can create your own by choosing you own colors for the border, background and link color.
* Multiple counter bullet formats to choose from; none, decimal, numeric and roman.
* Choose to display the table of contents hierarchical or not. This means headings of lower priority will be nested under headings of higher priority.
* User can optionally hide the table of contents. You full control of this feature. It can be disabled and you can choose to have it hidden by default.
* Supports smooth scrolling.
* Selectively enable or disabled the table of contents on a post by post basis.
* Choose which headings are used to generate the table of contents. This too can be set on a post by post basis.
* Easily exclude headers globally and on a post by post basis.
* If you rather not insert the table of contents in the post content, you can use the supplied widget and place the table of contents in your theme's sidebar.
* The widgets supports being affixed or stuck on the page so it is always visible as you scroll down the page. NOTE: this is an advanced option since every theme is different, you might need support from your theme developer to learn what the correct item selector to use in the settings to enable this feature.
* The widget auto highlights the sections currently visible on the page. The highlight color is configurable.
* Developer friendly with many action hooks and filters available. More can be added by request on [Github](https://github.com/shazahm1/Easy-Table-of-Contents). Pull requests are welcomed.

= TAKE IT A STEP FURTHER WITH EASY TABLE OF CONTENTS PRO =
With [EASY TABLE OF CONTENTS PRO](https://tocwp.com/pricing/) You will get access to more professional Settings, options and positions to really push your TOC to the next level.
* <strong>New - Gutenberg Block </strong>: Easily create TOC in Gutenberg block without the need of any coding or shortcode.
* <strong>New - Elementor Widget </strong>: Easily create TOC using Elementor Widget without the need of any coding or shortcode.
* <strong>New - Fixed/Sticky TOC </strong>: Users can find the content that they need, much faster through the option of sticky TOC.
* <strong>New - Full AMP Support </strong>: Generates a TOC with your existing setup and make it AMP compatible automatically.

### Support

We try our best to provide support on WordPress.org forums. However, We have a special [team support](https://magazine3.company/contact/) where you can ask us questions and get help. Delivering a good user experience means a lot to us and so we try our best to reply each and every question that gets asked.

### Bug Reports

Bug reports for Easy Table of Contents are [welcomed on GitHub](https://github.com/ahmedkaludi/Easy-Table-of-Contents). Please note GitHub is not a support forum, and issues that aren't properly qualified as bugs will be closed.

### [JOIN TELEGRAM GROUP COMMUNITY](https://t.me/+XADGN24lHNk0YjE1/)**: Purpose of this group is to get proper suggestions and feedback from plugin users and the community so that we can make the plugin even better.

### Live Examples

* [cMap Template Docs](http://connections-pro.com/documentation/cmap/)
* [Circled Template Docs](http://connections-pro.com/documentation/circled/)
* [Gridder Template Docs](http://connections-pro.com/documentation/gridder/)

### Roadmap 
* Fragment caching for improved performance.
* Improve SEO by adding options to add nofollow to TOC link and wrap TOC nav in noindex tag.
* Improve accessibility.
* Add Bullet and Arrow options for list counter style.

### Credit 

Easy Table Contents is a fork of the excellent [Table of Contents Plus](https://wordpress.org/plugins/table-of-contents-plus/) plugin by [Michael Tran](http://dublue.com/plugins/toc/).

### Screenshots 

1. The General section of the settings.
2. The Appearance section of the settings.
3. The Advanced section of the settings.

### Installation 

= Using the WordPress Plugin Search =

1. Navigate to the `Add New` sub-page under the Plugins admin page.
2. Search for `easy table of contents`.
3. The plugin should be listed first in the search results.
4. Click the `Install Now` link.
5. Lastly click the `Activate Plugin` link to activate the plugin.

= Uploading in WordPress Admin =

1. [Download the plugin zip file](http://wordpress.org/plugins/easy-table-of-contents/) and save it to your computer.
2. Navigate to the `Add New` sub-page under the Plugins admin page.
3. Click the `Upload` link.
4. Select Easy Table of Contents zip file from where you saved the zip file on your computer.
5. Click the `Install Now` button.
6. Lastly click the `Activate Plugin` link to activate the plugin.

= Using FTP =

1. [Download the plugin zip file](http://wordpress.org/plugins/easy-table-of-contents/) and save it to your computer.
2. Extract the Easy Table of Contents zip file.
3. Create a new directory named `easy-table-of-contents` directory in the `../wp-content/plugins/` directory.
4. Upload the files from the folder extracted in Step 2.
4. Activate the plugin on the Plugins admin page.

== Changelog ==

= 2.0.32 08/16/2022 =
* NEW: Added Sticky Table of Content #241
* TWEAK: Improved admin UI & UX #245
* TWEAK: Audit onboarding as a first time user #243
* TWEAK: Audit default options #242 #246
* BUG: Capitalizing the first letter of each title in the table of content #252
* BUG: Need to fix the sidebar position #251

= 2.0.31.1 08/03/2022 =
* BUG: TOC not working with the SEOWP theme #230
* BUG: TOC rendering area’s height is always changing in sidebar #244
* BUG: The colon is getting removed from anchor links #248
* BUG: After 2.0.27 version updates making conflict with Avada theme #229
* BUG: Need to fix Easy table of content in sidebar #232
* BUG: TOC causes problems after updating my latest post #234
* BUG: TOC showing issue with video implemented posts/pages. #236
* BUG: When using TOC with Elementor then the animation content is not showing #237

= 2.0.31 07/29/2022 =
BUG: Elementor editor is not accessible after latest update. #235

= 2.0.30 07/28/2022 =
* NEW: Added Hook Before/After Widget Container #119
* NEW: Added wysiwyg button to Wordpress visual editor #140
* TWEAK: Sticky Sidebar TOC improvements #226 
* TWEAK: Incorrect prefix in one function  #227
* BUG: Conflicts with WP-Typography #135
* BUG: TOC does not show up in woocommerce product description #224


= 2.0.29 07/19/2022 =
* TWEAK: Added Oxygen pagebulider compatibility #198
* TWEAK: Added toggle state class to container #129
* TWEAK: Added Refresh Toggle State #149
* BUG: TOC not showing in WooCommerce category description #134
* BUG: TOC links not working with emoji in title #117
* BUG: TOC not running on nested excluded filters #118
* BUG: Showing incorrect excerpt in a grid with Genesis Framework and other themes #144

= 2.0.28 07/15/2022 =
* TWEAK: Added Sidebar placement option for TOC #156
* TWEAK: Added SeedProd Pro compatibility #157
* TWEAK: Added option to show the TOC content after the first paragraph #181
* BUG: TOC not working in sidebar with Blocksy theme #220
* BUG: Form elements do not have associated labels In lighthouse #219
* BUG: Alternate Heading problem with Umlauts #148

= 2.0.27 07/12/2022 =
* TWEAK: Added subscribe to newsletters form on plugin activation #216
* TWEAK: Added user feedback form on plugin deactivation #216
* TWEAK: Added option to remove special characters from TOC Headings #217
* BUG: Corner Stone page builder heading are not working #200
* BUG: The links are not working using href with pure CSS option #208
* BUG: Attribute href is missing in an anchor element due to which links cannot be crawled #210
* BUG: Debug Warnings #212

= 2.0.26 07/05/2022 =
* BUG: TOC loading method should be same for CSS and JS #199
* BUG: Custom width option should come after selecting the User Define option #201
* BUG: Function added to front.js but not present in front.min.js #202
* BUG: The custom heading is not working with WP Bakery page builder #205
* BUG: TOC not working in the Avada themes in widgets #206
* BUG: Headers in content of shortcodes are not getting showing up in TOC #209
* BUG: TOC broken for non-English titles #211

= 2.0.25 06/27/2022 =
* TWEAK: Added Migration from Table of Contents Plus and LuckyWP Table of Contents #160
* TWEAK: Added Option to add inline CSS and JS #189
* TWEAK: Added Shortcode to show hidden view on particular posts #183
* TWEAK: Added Hyphen Counter to display the TOC heading #192
* TWEAK: Added Dot Counter to display the TOC heading #180
* TWEAK: Improved the Web Accessibility in TOC Toggle #190
* BUG: Shortcodes are not rendering in TOC titles #197
* BUG: TOC heading are getting hidden in sticky header #186
* BUG: No success or error message after support request is submitted #196
* BUG: Same font size appearing in headings and sub-headings #161
* BUG: Salient core plugin conflict with last update 2.0.24.1 #207

= 2.0.24.1 06/14/2022 =
* BUG: TOC not displaying properly when initial view option is disabled #195
* BUG: Initial View option not working with Pure CSS Loading Method #194

= 2.0.24 06/10/2022 =
* TWEAK: Added TOC in Infinite Scroll #138
* TWEAK: Improved the activation process #187
* BUG: TOC Toggle not working with Magnolia Theme #174
* BUG: Initial view not working with TOC Loading Method of CSS #179
* BUG: Toggle is not visible when Display Header option is disable #171
* BUG: CSS not loading when using shortcode in theme file #175
* BUG: the_content filter run twice #182
* BUG: Form UI looks ugly #169
* BUG: Debug Warnings in multibyte string functions #185

= 2.0.23 05/31/2022 =
* TWEAK: Added filter to modify anchor links #167
* TWEAK: Added filter to add TOC before or after the sidebar widget #166
* TWEAK: Added option to align TOC to center #158
* TWEAK: Design improvements in options panel #172

= 2.0.22 05/06/2022 =
* BUG: Double hyphens are getting removed from content issue fixed #163

= 2.0.21 05/06/2022 =
* BUG: Critical error fixed #147

= 2.0.20 05/05/2022 =
* TWEAK: Added Toggle with CSS for websites runs without jQuery #153
* TWEAK: Added telegram group join link for suggestions and feedback #159
* BUG: TOC links not jumping in some posts which have special characters #163
* BUG: Incorrect email ID updated in the plugin #165
* BUG: Proper documentation added for adding TOC with shortcodes & do_shortcode #152
* BUG: TOC links not working when do_shortcode added directly in the template #147
* BUG: TOC links not working with some specical character with Elementor #162

= 2.0.19 04/16/2022 =
* Bug Fixed : While Using Elementor Page builder TOC is not working when special characters are used in headings. #150
* Bug Fixed : Need to load CSS/JS files only on the selected post types. #154

= 2.0.18 03/29/2022 =
* TWEAK: Added Technical Support Tab in Settings Panel.

= 2.0.17 03/26/2021 =
* TWEAK: Add additional check to prevent `Uncaught Error: Call to undefined function is_woocommerce()`.
* TWEAK: Ensure an instance of `ezTOC_Post ` is returned before accessing methods/properties.

= 2.0.16 02/01/2021 =
* TWEAK: Remove special characters such as fancy quotes, en and, em dashes when generating in-page anchor IDs.

= 2.0.15 01/27/2021 =
* TWEAK: Remove additional reserved characters when generating in-page anchor IDs.

= 2.0.14 01/26/2021 =
* TWEAK: Refactor debug log as a Singleton.
* TWEAK: Add additional logging to aid in debugging.
* BUG: Correct logic for PHP where empty string no longer evaluates as integer `0`.

= 2.0.13 01/25/2021 =
* TWEAK: Restrict debug logging to when `WP_DEBUG` is enabled *and* current user capability of `manage_options`.
* TWEAK: Add logging to aid in support.
* DEV: phpDoc update.

= 2.0.12 01/22/2021 =
* TWEAK: Allow `_` and `-` in anchors.
* TWEAK: Minor CSS tweaks that prevent theme from breaking the layout.
* TWEAK: Minor tweak to class initialization.
* TWEAK: Do not display the view toggle if JavaScript is broken on the site.
* TWEAK: Add the ability to enable displaying of displaying debug information on the page.
* BUG: Check for array and keys before accessing values.
* BUG: Check for array key be fore access.
* BUG: Remove reserved characters when generating in-page anchor IDs.
* DEV: Remove unnecessary vendor library files.
* DEV: Deal with phpStorm showing a warning about path not found when including files.

= 2.0.11 05/01/2020 =
* COMPATIBILITY: Add support for the Uncode theme.
* COMPATIBILITY: Do not run on WooCommerce pages.
* DEV: Correct typo in phpDoc.

= 2.0.10 04/20/2020 =
* TWEAK: Add trailing `span` to heading, to prepare for `#` option and to fix duplicate heading title matching.
* TWEAK: Add second heading search/replace function to search for heading in content with heading html entities decoded. May help Beaver Builder users as it seems like it does not encode HTML entities as WP core does.


= 2.0.9 04/08/2020 =
* TWEAK: AMP/Caching plugins seems to break anchors with colons and periods even though they are valid characters for the id attribute in HTML5.
* TWEAK: Replace multiple underscores with a single underscore.
* DEV: Update the UWS library which fixes the deprecation notice for PHP 7.4.
* DEV: Add phpcs.xml.dist.
* DEV: Strict type checks.
* DEV: Inline doc updates.

= 2.0.8 04/03/2020 =
* TWEAK: Convert `<br />` tags in headings to a space.
* TWEAK: Add additional widget classes.
* TWEAK: Improve the sanitization of the excluded headings field post setting.
* TWEAK: Minor optimization of creating the matching pattern for excluding headings for improved performance.
* COMPATIBILITY: Exclude Create by Mediavine from heading eligibility.
* BUG: Ensure excluded headings are removed from the headings array.
* BUG: Ensure empty headings are removed from the headings array.

= 2.0.7 04/02/2020 =
* NEW: Exclude any HTML nodes with the class of `.ez-toc-exclude-headings`.
* TWEAK: Change smooth scroll selector from `'body a'` to `'a.ez-toc-link'`.
* TWEAK: Declare JS variables.
* TWEAK: Support unicode characters for the `id` attribute. Permitted by HTML5.
* TWEAK: Move the in-page anchor/span to before the heading text to account for long headings where it line wraps.
* TWEAK: Slight rework to ezTOC widget container classes logic.
* TWEAK: Cache bust the JS to make dev easier.
* TWEAK: JavaScript cleanup.
* TWEAK: URI Encode the id attribute to deal with reserved characters in JavaScript. Technically not necessary for the id attribute but needed to work with the jQuery smoothScroll library.
* COMPATIBILITY: Reintroduce filter to exclude Ultimate Addons for VC Composer Tabs from heading eligibility.
* BUG: Correct array iteration logic when processing headings.
* BUG: Tighten matching for headings in excluded HTML nodes. The loose matching was excluding far too many headings.
* BUG: Use `esc_attr()` instead of `esc_url()` for the anchor href because valid id attribute characters would cause it to return an empty href which cause a nonworking link.

= 2.0.6 03/30/2020 =
* BUG: Ensure minified files are current.

= 2.0.5 03/27/2020 =
* BUG: Prevent possible "strpos(): Empty needle in" warnings when excluding nodes from TOC eligibility.

= 2.0.4 03/16/2020 =
* NEW: Introduce the `ez_toc_container_class` filter.
* TWEAK: Slight rework to ezTOC container classes logic.
* BUG: `sprintf()` was eating `%` in the TOC heading item.
* BUG: Do not insert TOC at top of post if before first heading option is selected even if first heading can not be found. Some page builders cause the TOC to insert twice or on blog pages.

= 2.0.3 03/12/2020 =
* TWEAK: Slightly tighten heading matching, last update made it a little too loose.
* BUG: Correct logic required to place TOC before first heading which is required for the more lax heading matching required for page builders.

= 2.0.2 03/12/2020 =
* COMPATIBILITY: Remove filter to exclude Ultimate Addons for VC Composer Tabs from heading eligibility.
* COMPATIBILITY: Add additional filters to improve Elementor compatibility.
* TWEAK: Loosen heading matching when doing find/replace to insert in page links. Excluding the opening heading tag to allow matching heading where page builders dynamically add classes and id which break heading matching during find/replace.

= 2.0.1 03/09/2020 =
* COMPATIBILITY: Exclude the WordPress Related Posts plugin nodes.
* COMPATIBILITY: Exclude a couple Atomic Block plugin nodes.
* COMPATIBILITY: Exclude JetPack Related Posts from heading eligibility.
* COMPATIBILITY: Exclude Ultimate Addons for VC Composer Tabs from heading eligibility.
* COMPATIBILITY: Exclude WP Product Reviews from heading eligibility.
* TWEAK: Prevent possible "strpos(): Empty needle in" warnings when excluding nodes from TOC eligibility.

= 2.0 02/01/2020 =
* NEW: Major rewrite of all code and processing logic to make it faster and more reliable.
* NEW: Support for the <!--nextpage--> tag.
* NEW: Introduce helper functions for devs.
* NEW: Support WPML.
* NEW: Support Polylang.
* NEW: Add filter to support the Rank Math plugin.
* NEW: Introduce the `ez_toc_maybe_apply_the_content_filter` filter.
* TWEAK: Improve translation compatibility.
* TWEAK: Rework widget logic to allow multi-line TOC items, improve active item highlighting while removing the use of the jQuery Waypoints library.
* TWEAK Add additional classes to TOC list items.
* TWEAK: Add WOFF2 format for icon format and change font references in CSS.
* TWEAK: Add font-display: swap for toggle icon.
* TWEAK: Update JS Cookie to 2.2.1.
* TWEAK: Update jQuery Smooth Scroll to 2.2.0.
* TWEAK: Allow forward slash and angle brackets in headings and alternate headings.
* TWEAK: Allow forward slash in  excluded headings.
* TWEAK: Remove new line/returns when matching excluded headings.
* TWEAK: Simple transient cache to ensure a post is only processed once per request for a TOC.
* TWEAK: Improve sanitization of alternate headings field value.
* TWEAK: Deal with non-breaking-spaces in alternate headings.
* TWEAK: Add the ability to exclude by selector content eligible to be included in the TOC.
* TWEAK: Change the shortcode priority to a higher value.
* TWEAK: Add filter to remove shortcodes from the content prior to the `the_content` filter being run to exclude shortcode content from being eligible as TOC items.
* TWEAK: Add compatibility filters to remove shortcodes for Connections and Striking theme to remove them from eligible TOC item content.
* TWEAK: Do not execute if root current filter is the `wp_head` or `get_the_excerpt` filters.
* TWEAK: Add filter to exclude content by selector.
* TWEAK: Move in-page anchor to after the heading instead of wrapping the heading to prevent conflicts with theme styling.
* TWEAK: Utilize the `ez_toc_exclude_by_selector` filter the exclude the JetPack share buttons from eligible headings.
* TWEAK: Remove the Elegant Themes Bloom plugin node from the post content before extracting headings.
* TWEAK: Add compatibility filter for the Visual Composer plugin.
* TWEAK: Utilize the `ez_toc_exclude_by_selector` filter the exclude the Starbox author heading from eligible headings.
* I18N: Add wpml-config.xml file.
* BUG: Correct option misspelling.
* BUG: Do not need to run values for alternate and exclude headings thru `wp_unslash()` because `update_post_meta()` already does.
* BUG: Do not need to run `stripslashes()` when escaping the alternate heading value.
* BUG: Sanitize the excluded heading string before saving post meta.
* DEV: Change PHP keywords to comply with PSR2.
* DEV:Bump minimum PHP version to 5.6.20 which matches WP core.

= 1.7 05/09/2018 =
* NEW: Introduce the `ez_toc_shortcode` filter.
* TWEAK: Fix notices due to late eligibility check. props unixtam
* TWEAK: Tweak eligibility check to support the TOC widget.
* TWEAK: Prefix a few CSS classes in order to prevent collisions with theme's and other plugins.
* TWEAK: Avoid potential PHP notice in admin when saving the post by checking for nonce before validating it.
* TWEAK: Using the shortcode now overrides global options.
* TWEAK: `the_content()` now caches result of `is_eligible()`.
* TWEAK: Refactor to pass the WP_Post object internally vs. accessing it via the `$wp_query->post` which may not in all cases exist.
* TWEAK: Use `pre_replace()` to replace one or more spaces with an underscore.
* TWEAK: Return original title in the `ez_toc_url_anchor_target` filter.
* TWEAK: Strip `&nbsp;`, replacing it with a space character.
* TWEAK: Minor tweaks to the in page URL creating.
* TWEAK: Wrap TOC list in a nav element.
* TWEAK: Init plugin on the `plugins_loaded` hook.
* TWEAK: Tweak the minimum number of headers to 1.
* BUG: The header options from the post meta should be used when building the TOC hierarchy, not the header options from the global settings.
* BUG: Do not double escape field values.
* BUG: Ensure Apostrophe / Single quote use in Exclude Headings work.
* OTHER: Update CSS to include the newly prefixed classes.
* DEV: Remove some commented out unused code.

= 1.6.1 03/16/2018 =
* TWEAK: Revert change made to allow HTML added via the `ez_toc_title` filter as it caused undesirable side effects.
* BUG: Ensure Smooth Scroll Offset is parsed as an integer.

= 1.6 03/15/2018 =
* NEW: Add `px` option for font size unit.
* NEW: Add title font size and weight settings options.
* NEW: Add the Mobile Smooth Scroll Offset option.
* TWEAK: Change default for font size unit from `px` to `%` to match the default options values.
* TWEAK: Correct CSS selector so margin is properly applied between the title and TOC items.
* TWEAK: Honor HTML added via `ez_toc_title` filter.
* TWEAK: Ensure the ezTOC content filter is not applied when running `the_content` filter.
* TWEAK: Only enqueue the javascript if the page is eligible for a TOC.
* TWEAK: Update icomoon CSS to remove unecessary CSS selectors to prevent possible conflicts.
* TWEAK: The smooth scroll offset needs to be taken into account when defining the offset_top property when affixing the widget.
* OTHER: Update frontend minified CSS file.
* OTHER: Update the frontend minified javascript file.
* DEV: phpDoc corrections.

= 1.5 02/20/2018 =
* BUG: Correct CSS selector to properly target the link color.
* OTHER: Update the WayPoints library.
* DEV: Add a couple @todo's.

= 1.4 01/29/2018 =
* TWEAK: Change text domain from ez_toc to easy-table-of-contents.
* TWEAK: Rename translation files with correct text domain.
* BUG: Ensure page headers are processed to add the in page header link when using the shortcodes.
* BUG: Add forward slash to domain path in the plugin header.
* I18N: Update POT file.
* I18N: Update Dutch (nl_NL) translation.

= 1.3 12/18/2017 =
* FEATURE: Add support for the `[ez-toc]` shortcode.
* NEW: For backwards compatibility with "Table of Content Plus", register the `[toc]` shortcode.
* NEW: Introduce the `ez_toc_extract_headings_content` filter.
* TWEAK: Update the tested to and required readme header text.
* TWEAK: Do not show the widget on the 404, archive, search and posts pages.
* I18N: Add the nl_NL translation.

= 1.2 04/29/2016 =
* TWEAK: Remove the font family from styling the TOC title header.
* TWEAK: Pass the raw title to the `ez_toc_title` filter.
* BUG: A jQuery 1.12 fix for WordPress 4.5.

= 1.1 02/24/2016 =
* FEATURE: Add option to replace header wither alternate header text in the table of content.
* NEW: Introduce the ez_toc_filter.
* NEW: Introduce ezTOC_Option::textarea() to render textareas.
* NEW: Introduce array_search_deep() to recursively search an array for a value.
* TWEAK: Run table of contents headers thru wp_kses_post().
* TWEAK: Escape URL.
* TWEAK: Count excluded headings only once instead of multiple times.
* TWEAK: Escape translated string before rendering.
* TWEAK: Use wp_unslash() instead of stripslashes().
* TWEAK: Escape translated string.
* BUG: Fix restrict path logic.
* OTHER: Readme tweaks.
* I18N: Add POT file.
* I18N: Add Dutch translation.
* DEV: Update .gitignore to allow PO files.
* DEV: phpDoc fix.

= 1.0 09/08/2015 =
* Initial release.
  - Complete refactor and restructure of the original code for better design and separation of function to make code base much easier to maintain and extend.
  - Update all third party libraries.
  - Make much better use of the WordPress Settings API.
  - Minified CSS and JS files are used by default. Using SCRIPT_DEBUG will use the un-minified versions.
  - Add substantial amounts of phpDoc for developers.
  - Add many hooks to permit third party integrations.
  - Widget can be affixed/stuck to the page so it is always visible.
  - Widget will highlight the table of content sections that are currently visible in the browser viewport.
  - Widget will now generate table of contents using output from third party shortcodes.
  - Use wpColorPicker instead of farbtastic.
  - Remove all shortcodes.
  - Per post options are saved in post meta instead of set by shortcode.

== Frequently Asked Questions ==

= Ok, I've installed this... what do I do next? =

You first stop should be the Table of Contents settings admin page. You can find this under the Settings menu item.

You first and only required decision is you need to decide which post types you want to enable Table of Contents support for. By default it is the Pages post type. If on Pages is the only place you plan on using Table of Contents, you have nothing to do on the Settings page. To keep things simple, I recommend not changing any of the other settings at this point. Many of the other settings control when and where the table of contents is inserted and changing these settings could cause it not to display making getting started a bit more difficult. After you get comfortable with how this works... then tweak away :)

With that out of the way make sure to read the **How are the tables of contents created?** FAQ so you know how the Table of Contents is automatically generated. After you have the page headers setup, or before, either way... Scroll down on the page you'll see a metabox named "*Table of Contents*", enable the *Insert table of contents.* option and Update and/or Publish you page. The table of contents should automatically be shown at the top of the page.

= How are the tables of contents created? =

The table of contents is generated by the headers found on a page. Headers are the [`<h1>,<h2>,<h3>,<h4>,<h5>,<h6>` HTML tags](http://www.w3schools.com/tags/tag_hn.asp). If you are using the WordPres Visual Post Editor, these header tags are used and inserted into the post when you select one of the [*Heading n* options from the formatting drop down](http://torquemag.io/wordpress-heading-tags/). Each header that is found on the page will create a table of content item. Here's an example which will create a table of contents containing the six items.

`<h1>Item 1</h1>
<h1>Item 2</h1>
<h1>Item 3</h1>
<h1>Item 4</h1>
<h1>Item 5</h1>
<h1>Item 6</h1>`

You can also create "nested" table of contents. This is difficult to explain so I'll illustrate building on the previous example. In this example a table of contents will be created with the same six items but now the first three will each an child item nested underneath it. The indentation is not necessary, it was only added for illustration purposes.

`<h1>Item 1</h1>
    <h2>Item 1.1 -- Level 2</h2>
<h1>Item 2</h1>
    <h2>Item 2.1 -- Level 2</h2>
<h1>Item 3</h1>
    <h2>Item 3.1 -- Level 2</h2>
<h1>Item 4</h1>
<h1>Item 5</h1>
<h1>Item 6</h1>`

You are not limited to a single a single nested item either. You can add as many as you need. You can even create multiple nested levels...

`<h1>Item 1</h1>
    <h2>Item 1.1 -- Level 2</h2>
        <h3>Item 1.1.1 -- Level 3</h3>
        <h3>Item 1.1.2 -- Level 3</h3>
        <h3>Item 1.1.3 -- Level 3</h3>
    <h2>Item 1.2 -- Level 2</h2>
      <h3>Item 1.2.1 -- Level 3</h3>
      <h3>Item 1.2.2 -- Level 3</h3>
      <h3>Item 1.2.3 -- Level 3</h3>
    <h2>Item 1.3 -- Level 2</h2>
<h1>Item 2</h1>
    <h2>Item 2.1 -- Level 2</h2>
    <h2>Item 2.2 -- Level 2</h2>
<h1>Item 3</h1>
    <h2>Item 3.1 -- Level 2</h2>
    <h2>Item 3.2 -- Level 2</h2>
<h1>Item 4</h1>
<h1>Item 5</h1>
<h1>Item 6</h1>`

You can nest up 6 levels deep if needed. I hope this helps you understand how to create and build your own auto generated table of contents on your sites!

= Is there any shortcode to add the table of content to anywhere I want ? =

Yes you can add the TOC with this shortcode – [ez-toc] and with the help of this you can easily add the TOC in the content or anywhere in the WordPress and if you want to add the shortcode on the theme file then you can add it with the help of this code – <?php echo do_shortcode( ‘[ez-toc]’ ); ?> and with this, you can add the TOC on any file according to your need.

== Upgrade Notice ==

= 1.0 =
Initial release.

= 1.3 =
Requires WordPress >= 4.4 and PHP >= 5.3. PHP version >= 7.1 recommended.

= 1.4 =
Requires WordPress >= 4.4 and PHP >= 5.3. PHP version >= 7.1 recommended.

= 1.5 =
Requires WordPress >= 4.4 and PHP >= 5.3. PHP version >= 7.1 recommended.

= 1.6 =
Requires WordPress >= 4.4 and PHP >= 5.3. PHP version >= 7.1 recommended.

= 1.6.1 =
Requires WordPress >= 4.4 and PHP >= 5.3. PHP version >= 7.1 recommended.

= 1.7 =
Requires WordPress >= 4.4 and PHP >= 5.3. PHP version >= 7.1 recommended.

= 2.0-rc4 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.1 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.2 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.3 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.4 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.5 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.6 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.7 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.8 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.9 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.10 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.11 =
Requires WordPress >= 5.0 and PHP version >= 5.6.20 (>= 7.1 is recommended).

= 2.0.12 =
Requires WordPress >= 5.3 and PHP version >= 5.6.20 (>= 7.4 is recommended).

= 2.0.13 =
Requires WordPress >= 5.3 and PHP version >= 5.6.20 (>= 7.4 is recommended).

= 2.0.14 =
Requires WordPress >= 5.3 and PHP version >= 5.6.20 (>= 7.4 is recommended).

= 2.0.15 =
Requires WordPress >= 5.3 and PHP version >= 5.6.20 (>= 7.4 is recommended).

= 2.0.16 =
Requires WordPress >= 5.3 and PHP version >= 5.6.20 (>= 7.4 is recommended).

= 2.0.17 =
Requires WordPress >= 5.3 and PHP version >= 5.6.20 (>= 7.4 is recommended).
