# Stop Search Spam

[![WordPress tested](https://img.shields.io/badge/WordPress-tested%20up%20to%207.0-3858e9.svg)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-5.6%2B-777bb4.svg)](https://www.php.net/)
[![License](https://img.shields.io/badge/license-GPL--2.0%2B-green.svg)](https://www.gnu.org/licenses/gpl-2.0.html)
[![Version](https://img.shields.io/badge/version-1.0.0-informational.svg)](readme.txt)

Protect your WordPress site from internal search spam that can pollute indexed search-result pages and damage SEO.

Spammers often abuse WordPress search URLs like `example.com/?s=spam-term` or `/search/spam-term/` by injecting promotional text, suspicious domains, foreign-language keyword stuffing, emoji tricks, and long search phrases. WordPress may generate a search results page for those terms, and search engines or spam backlink systems can discover those URLs.

Stop Search Spam blocks those abusive search requests before they become a ranking, indexing, or reputation problem.

## What It Protects Against

- Long spam phrases injected into search URLs
- Keyword stuffing through internal search pages
- Spam URLs built from your own domain
- Unwanted foreign alphabet patterns in search terms
- Emoji and special-symbol bypass attempts
- Search-result pages that can become low-quality indexed content

## Key Features

- Block malicious internal search queries automatically.
- Limit the maximum length of search strings.
- Filter selected character sets, including Chinese and Cyrillic characters.
- Disable emojis and special symbols in search terms.
- Protect organic search visibility by reducing spam-generated result pages.
- Keep the plugin lightweight and easy to configure.

## Requirements

- WordPress 4.3 or later
- PHP 5.6 or later

## Installation

1. Upload the plugin folder to `/wp-content/plugins/stop-search-spam`.
2. Activate **Stop Search Spam** from **Plugins** in WordPress.
3. Open **Settings -> Stop Search Spam** and configure your filters.

## Recommended Setup

- Set a practical maximum search length for your site.
- Block character sets that are not relevant to your audience.
- Disable emoji search input if your site does not need it.
- Monitor search traffic and tune rules if legitimate visitors use multilingual search.

## Changelog

### 1.0.0

- Initial release.

## License

Stop Search Spam is licensed under the GPL v2 or later.
