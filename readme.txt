=== Region Detect ===
Contributors: joebrewer
Donate link: http://www.brewsterware.com/region-detect-wordpress-plugin.html
Tags: geolocation, country detection, localisation, localization
Requires at least: 3.1.2
Tested up to: 3.6.1
Stable tag: 1.02.05

A plugin that allows personalisation by displaying the visitors country name in posts and pages.

== Description ==

Region detect is a plugin for Wordpress that detects the country that the current visitor is browsing from.

It can display the country to the user; something like: Hello visitor from Spain! or display a flag of the country. The plugin also makes the ISO 3166-1 country code and country name avaliable to other plugins.

== Installation ==

1. Extract the zip file and just drop the contents in the <code>wp-content/plugins/</code> directory of your WordPress installation.
2. Activate the plugin through the 'Plugins' page.
3. Copy the MaxMind country database to the plugin folder, or add your MaxMind license key to the plugin admin panel.
4. If you are using the web service enable caching and select the cache length that you need.
5. Use %%COUNTRYCODE%% or %%COUNTRYNAME%% in your posts to display the two character country code or country name respectively.

== Frequently Asked Questions ==

= Do I have to pay for the MaxMind database? =

No, MaxMind offer a free version of the database. However the paid for version is more accurate.

= I am a wordpress developer and want to access the country code or name in my code. How do I do that? =

Easy :-) Just declare the global variables $rdISO3166_1 or $rdCountryName in your code and away you go.

== Screenshots ==

Screen shots of the options page with detailed explanations of the options can be found on the [Region Detect support page](http://www.brewsterware.com/region-detect-wordpress-plugin.html)

== Changelog ==

= 1.00.00 =
* Initial version

= 1.01.00 =
* Added option to set the country from the url

= 1.02.00 =
* Corrected bug with the cache clearing too quickly
* Added a table that shows countries and number of ip addresses that are cached

= 1.02.01 =
* Corrected spelling mistakes

= 1.02.02 =
* Removed debugging code

= 1.02.04 =
* Fixed installation bug which was causing a crash when installing

= 1.02.05 =
* Made plugin multisite compliant

== Upgrade Notice ==

= 1.00.00 =
This is the initial version.

= 1.01.00 =
This version adds the ability to set the country from the url. Deactivate and reactivate the plugin to upgrade.

= 1.02.00 =
Fixes a bug with the cache and added all country codes from the ISO 3166-1 set. Deactivate and reactive the plugin to upgrade.

= 1.02.05 =
* Made plugin multisite compliant