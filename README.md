# WooCommerce Dash Docset

A docset of [WooCommerce][1] for the popular Mac OS X app [Dash][2].

## In-App Installation

With the introduction of [User-Contributed Docsets in Dash 2.1+][3], you can now install the WooCommerce Docset by searching within Dash.

1. Launch **Dash**
2. Open Dash's Preferences (⌘,) then select the **Downloads** tab
3. In the sidebar under **Other Docsets**, select _**User Contributed**_
4. Search for **WooCommerce**
5. Click on the **Download** button to install

You'll now receive auto-updates when the docset has been updated!

## Manual Installation

1. Download a Zip archive of this repository
2. Extract the file to your Desktop
3. Copy **WooCommerce.docset** to `~/Library/Application Support/Dash/Docsets/WooCommerce`
4. Launch Dash
5. Open Dash's Preferences (⌘,) then select the **Docsets** tab
6. Click the **Rescan** button
7. _WooCommerce_ will appear in the list of installed Docsets

## Manual Command Line Installation

If you prefer using a Terminal to the Finder, use the following commands:

1. `mkdir -p ~/"Library/Application Support/Dash/DocSets/WooCommerce" && cd "$_"`
2. `curl -#OkL https://github.com/ryanjbonnell/WooCommerce.docset/archive/master.tar.gz`
3. `tar -xzf master.tar.gz --strip-components 1 && rm master.tar.gz`
4. `open WooCommerce.docset`

An even more succinct version is:

`mkdir -p ~/"Library/Application Support/Dash/DocSets/WooCommerce" && cd "$_" && curl -#kL https://github.com/ryanjbonnell/WooCommerce.docset/archive/master.tar.gz | tar -xz --strip-components 1 && open WooCommerce.docset`

### Changelog

* 2.1.9 — 27 May 2014
* 2.1.8 — 30 April 2014

[1]: http://www.woothemes.com/woocommerce/
[2]: http://kapeli.com/dash
[3]: http://blog.kapeli.com/dash-2-dot-1
