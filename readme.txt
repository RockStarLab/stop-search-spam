=== Stop Search Spam ===
Contributors: RockstarLab
Tags: search, spam, anti-spam, search plugin, search spam
Requires at least: 4.3
Tested up to: 7.0
Stable tag: 1.0.0
Requires PHP: 5.6
License: GPL v2 or later

The plugin blocks internal site search spam (what lowers your site's ranking in the Google). 

== Description ==

= Stop Search Spam = 

Did you know that spammers can exploit your WordPress internal site search to advertise their illicit goods and services? 

Many WordPress websites have a built-in search function accessible via URLs like `example.com/?s=search_term` (or `example.com/search/search_term/`). Malicious bots and spammers abuse this by injecting long promotional texts, links, and unwanted keywords right into your search URLs. For example, they might use `example.com/?s=buy-fake-goods-from-my-site.com`. 

Because WordPress generates a search results page containing these terms, these dynamically generated pages can get crawled and indexed by Google or built into malicious backlink profiles. This creates unauthorized "adverts" on your domain, which leads to severe SEO penalties, keyword dilution, and a damaged site reputation.

**Stop Search Spam** is a powerful, lightweight security plugin designed to block internal WordPress site search spam and protect your Google SEO rankings. 

**Key Features & SEO Protection:**
* **Block Search Spam:** Automatically prevents malicious search queries and injected spam from being processed.
* **Protect SEO & Rankings:** Stops your search result pages from being hijacked for spam indexing, keeping your organic search rankings safe.
* **Limit Query Length:** Set a strict maximum character limit for search strings to instantly block long spam phrases and URLs.
* **Filter Foreign Alphabets:** Easily disallow specific character sets, including Chinese and Cyrillic (Russian) characters, often used in automated search spam.
* **Disable Emojis in Search:** Prevent spammers from circumventing filters using emojis and special symbols.

Keep your website's search clean, fast, and secure!

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/stop-search-spam` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Use the Settings -> Stop Search Spam screen to configure the plugin

== Screenshots ==

1. Settings
2. Spam
3. Before
4. After

== Changelog ==

= 1.0.0 =
* Initial release.

== Upgrade Notice ==

`<?php code(); // goes in backticks ?>`