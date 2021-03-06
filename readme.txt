=== CampTix Event Ticketing ===
Contributors: automattic, kovshenin, andreamiddleton
Tags: ticketing, event ticketing
Requires at least: 3.5
Tested up to: 3.5.1
Stable tag: 1.3.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Simple and Flexible ticketing brought to you by WordCamp.org

== Description ==

CampTix is an easy to use and flexible event ticketing plugin created by WordCamp.org. Allow visitors to purchase tickets to your online or offline event, directly from your WordPress website.

* Multiple tickets and attendees forms
* Coupon codes for discounts
* Mass e-mail attendees
* Export attendees data into CSV or XML
* Public attendees list
* Revenue reports and summaries
* and much more!

Feel free to post your feature requests, issues and pull requests to [CampTix on GitHub](https://github.com/automattic/camptix "CampTix on GitHub").

== Installation ==

1. Download and extract CampTix in your `wp-content/plugins` directory
1. Activate the plugin through the Plugins menu in WordPress
1. Go to Tickets - Setup to configure your event settings and payment methods
1. Creat a ticket or two, place the `[camptix]` shortcode on a Page
1. Start selling!

For more information, visit the [Getting Started](https://github.com/automattic/camptix/wiki "Getting Started") guide on CampTix Wiki.

== Screenshots ==

1. Ticket sales table
2. Attendee registration form
3. Attendee admin view
4. Summarize by ticket type
5. Summarize by purchase day of week
6. Revenue report
7. Mass e-mail attendees

== Changelog ==

= 1.3.1
* Better escaping and sanitization
* Better error messages during failed payments
* Fixed a bug where the shortcode would display in plain text
* Other minor bug fixes and clean ups

= 1.3 =
* Added the ability to edit confirmation e-mails
* Reworked ticket questions, both under the hood and UI
* Added support to edit new and existing questions
* Added a bunch of currencies for PayPal
* Few bug fixes and minor enhancements

= 1.2.1 =
* Numerous bugs fixed
* RTL stylesheets
* Predefined PayPal credentials with a filter
* French and Hebrew translations: props xibe and maor
* New currency: ILS

= 1.2 =
* Added and API for payment methods
* Enhanced logging around payments
* UI cleanup in ticket questions
* Invalidate attendees list shortcode when an attendee is changed
* Improved admin columns in attendees, tickets and coupons
* Added GBP currency to PayPal
* Enabled meta logging addon by default
* Added textarea and radio question types
* Added column attribute to the [camptix_attendees] shortcode
* Added a couple of language packs
* Minor cleanups and bugfixes

= 1.1 =
* Added JPY currency
* Added l10n functions
* Removing closure functions to support php 5.2
* Questions v2 now a public feature
* Minor cleanups, bugfixes and enhancements

= 1.0 =
* First version
