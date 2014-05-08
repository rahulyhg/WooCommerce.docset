# WooCommerce Dash Docset

A docset of [WooCommerce][1] for the popular Mac OS X app [Dash][2].

## Installation

1. Download a Zip archive of this repository
2. Extract the file to your Desktop
3. Copy **WooCommerce.docset** to `~/Library/Application Support/Dash/Docsets/WooCommerce`
4. Launch Dash
5. Open Dash's Preferences (⌘,) then select the **Docsets** tab
6. Click the **Rescan** button
7. _WooCommerce_ will appear in the list of installed Docsets

## Alternate Installations

If you prefer using a Terminal to the Finder, use the following commands:

1. `mkdir -p ~/"Library/Application Support/Dash/DocSets/WooCommerce" && cd "$_"`
2. `curl -#OkL https://github.com/ryanjbonnell/WooCommerce.docset/archive/master.tar.gz`
3. `tar -xzf master.tar.gz --strip-components 1 && rm master.tar.gz`
4. `open WooCommerce.docset`

An even more succinct version is:

1. `mkdir -p ~/"Library/Application Support/Dash/DocSets/WooCommerce" && cd "$_" && curl -#kL https://github.com/ryanjbonnell/WooCommerce.docset/archive/master.tar.gz | tar -xz --strip-components 1 && open WooCommerce.docset`

## Changelog

**Version 2.1.8** (30 April 2014)

[1]: http://www.woothemes.com/woocommerce/
[2]: http://kapeli.com/dash
