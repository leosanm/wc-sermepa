=== WooCommerce Sermepa payment gateway ===
Contributors: jesusangel
Tags: ecommerce, e-commerce, commerce, wordpress woocommerce, payment, plugin, gateway, servired, sermepa, redsys
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=jesusangel.delpozo@gmail.com&item_name=Donation+for+WC-Sermepa
Requires at least: 3.3
Tested up to: 4.5.2
Stable tag: 1.0.11
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

WooCommerce redsys payment gateway is a payment gateway for WooCommerce.

== Description ==

Allow users to pay with theirs credit card trought redsys gateway.

= GET INVOLVED =

Developers can checkout and contribute to the source code on the [WC Sermepa GitHub Repository](http://github.com/jesusangel/wc-sermepa/).

== Installation ==

= Minimum Requirements =

* WordPress 3.3 or greater
* PHP version 5.2.4 or greater
* MySQL version 5.0 or greater
* WooCommerce 1.6 or greater
* Fsockopen support required
* Mcrypt support required

= Automatic installation =

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don’t even need to leave your web browser. To do an automatic install of WC-Sermepa, log in to your WordPress admin panel, navigate to the Plugins menu and click Add New.

In the search field type “WC-Sermepa” and click Search Plugins. Once you’ve found our payment gateway plugin you can view details about it such as the the point release, rating and description. Most importantly of course, you can install it by simply clicking Install Now. After clicking that link you will be asked if you’re sure you want to install the plugin. Click yes and WordPress will automatically complete the installation.

= Manual installation =

The manual installation method involves downloading our payment plugin and uploading it to your webserver via your favourite FTP application.

1. Download the plugin file to your computer and unzip it
2. Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your WordPress installation’s wp-content/plugins/ directory.
3. Activate the plugin from the Plugins menu within the WordPress admin.

= Upgrading =

Automatic updates should work a charm; as always though, ensure you backup your site just in case.

If on the off chance you do encounter issues with the shop/category pages after an update you simply need to flush the permalinks by going to WordPress > Settings > Permalinks and hitting 'save'. That should return things to normal.

== Frequently Asked Questions ==

= Does this plugin work for WooCommerce 1.6? =

Yes. Since stable tag 4, the plugin works on both WooCommerce 1.6 and 2.x versions. 

= Where can I find WC-Sermepa documentation and user guides =

http://wordpress.org/support/plugin/woocommerce-sermepa-payment-gateway

= Where can I request new features? =

http://wordpress.org/support/plugin/woocommerce-sermepa-payment-gateway

= Where can I report bugs or contribute to the project? =

Bugs can be reported on the [WC-Sermepa GitHub repository](https://github.com/jesusangel/wc-sermepa/issues).

= WC-Sermepa is awesome! Can I contribute? =

Yes you can! Join in on our [GitHub repository](http://github.com/jesusangel/wc-sermepa/) :)

== Screenshots ==

1. The slick WooCommerce settings panel
2. WooCommerce products admin
3. WooCommerce sales reports

== Changelog ==

= 1.0.11 - 22/05/2016
* Pull request (@enbata): Added filters to allow order_id customization: wc_myredsys_merchant_order_encode and wc_myredsys_merchant_order_decode

= 1.0.10 - 22/05/2016
* Added option to select protocol for Redsys notifications URL. Select HTTP if your site uses SSL with SNI (shared IP). Remember to allow Redsys gateway to reach your site via HTTP.
* Fixed some translations

= 1.0.9 - 11/04/2016
* Fixed wrong HTTPS link

= 1.0.8 - 24/12/2015
* Fixed redirect URL for WC < 2.1

= 1.0.7 - 12/12/2015
* Fixed redefined Services_JSON class error

= 1.0.6 - 08/12/2015
* Replaced home_url with plugin_url to support sites with different plugin folder.

= 1.0.5 - 19/11/2015
* Fix compatibility issue with WooCommerce <= 2.1

= 1.0.4 - 19/11/2015
* Fix. Bug with product description and WC < 2.1

= 1.0.3 - 14/11/2015
* Fix. Manage missing Mcrypt extension
* Added filter (wc_redsys_icon) to change redsys logo. Thanks to @oscarestepa

= 1.0.2 - 04/11/2015
* Fix. Hide notification about SHA256 key

= 1.0.1 - 04/11/2015
* Added notice to remember user must get a new SHA256 key

= 1.0.0 - 31/10/2015
* Added SHA256 signature
* Select payment method (card & Iupay)
* Shows TPV with customer's language

= 0.9.1 - 15/02/2015
* Fixed syntax error
* Removed deprecated add_inline_js method call

= 0.8 - 11/02/2015
* Removed deprecated logger method call

= 0.7 - 20/03/2014
* Added more currencies
* Added delay to redirect message

= 1 - 26/09/2013
* Updated to works on both WooCommerce 1.6 and 2.x or greater.

= 0.1 - 26/12/2012 =
* Initial version
