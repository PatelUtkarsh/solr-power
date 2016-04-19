# Solr Search for WordPress #
**Contributors:** getpantheon, Outlandish Josh, 10up, collinsinternet  
**Tags:** search  
**Requires at least:** 4.2
**Tested up to:** 4.5
**Stable tag:** 0.3
**License:** GPLv2 or later
**License URI:** http://www.gnu.org/licenses/gpl-2.0.html  

Improve your user experience with the Apache Solr search engine for your WordPress website.

## Description ##

Search is critical for your site, but the default search for WordPress leaves a lot to be desired. Improve your user experience with the Apache Solr search engine for your WordPress website.

* Fast results, with better accuracy
* Enables faceting on fields such as tags, categories, author, and page type.
* Indexing and faceting on custom fields
* Completely replaces default WordPress search, just install and configure.
* Completely integrated into default WordPress theme and search widget.
* Very developer-friendly: uses the modern [Solarium](http://www.solarium-project.org/) library

## Installation ##

First install the plugin as per normal. If you are installing on Pantheon, you will need to enable the Apache Solr add-on within the Pantheon Site Dashboard before you can enable the plugin.

1. Index your existing content by going to the plugin options screen and selecting the applicable **Actions**:
 - **Index Searchable Post Types**
2. Search on! Use the **Query** tab to validate indexing options.
3. See the examples/template directories for more rich implementation guidelines.

## Development ##

This plugin is under active development on GitHub:

[https://github.com/pantheon-systems/solr-power](https://github.com/pantheon-systems/solr-power)

Please feel free to file issues there. Pull requests are also welcome!

## Changelog ##

### 0.3 ###
* Bug fixes
* Settings page updates
* Filters for AJAX/Admin integration
* Indexing all publicly queryable post types
* Debug Bar Extension
* Default sort option on settings page
* Initial WP CLI integration

### 0.2 ###
* Works "out of the box" by overriding WP_Query()
* Much improved internal factoring

### 0.1 ###
* Initial alpha release (GitHub only)

### 0.0 ###
* Note this started as a fork of this wonderful project: https://github.com/mattweber/solr-for-wordpress
