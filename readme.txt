=== Ice Dragon Paywall ===
Contributors: icedr4gon
Requires at least: 5.0.0
Requires PHP: 7.0.0
Tested up to: 5.3.2
Stable tag: trunk
Tags: bitcoin, lightning, lightning network, metered paywall, paywall, metered, pay wall, content monetization, metered access, metered pay wall, paid content
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A Lighning Network enabled paywall for WordPress! Monetize your content today. Easy and fast setup ⚡

== Description ==

*This plugin is still only meant for Alpha testers! The platform is not stable.*

[Ice Dragon](https://ice-dragon.ch/) is a service that helps you to get paid for your content in Bitcoin over the Lightning Network!
It completely removes the burden of running and integrating Lightning Network components from you, so you can focus on creating content.

While Ice Dragon is platform-agnostic and you may use it on various platforms, this plugin helps you to integrate the service into your instance of Wordpress. Just register your content on [ice-dragon.ch](https://ice-dragon.ch/), install and configure the plugin, activate it for whatever pages or posts you'd like and start earning Bitcoin for your content!

**Features**

* Metered paywall: Let your readers read X number of characters for free and the rest only after a successful payment
* Flexible restrictions: restrict by entire post type, category, tag, taxonomy, or even on individual posts


We love contributions! Head over to our [GitHub page](https://github.com/ln-ice-dragon/ice-dragon-wp-plugin) if your feeling inspired 🙏


== Installation ==

1. Upload the entire `ice-dragon-wp-plugin` folder to your `/wp-content/plugins/` folder.
1. Go to the 'Plugins' page in the menu and activate the plugin.
1. Register your content on [ice-dragon.ch](https://ice-dragon.ch).
1. Copy your secret key from ice-dragon.ch to your plugin, and configure where you want a paywall to appear.

== Frequently Asked Questions ==

= How does Ice Dragon work? =

Users may buy access to your content on [ice-dragon.ch](https://ice-dragon.ch) over a short time period they can choose. You can configure paywalls globally for your WP site and there is a visibility setting on the post edit screen that lets you override the global settings. EG: Posts always show a paywall but this one does not.

= How does Lightning work? =

It's not very easy to grasp and setup at first, but once you've overcome the initial hurdles it's very easy and comfortable to use! Your users will need Bitcoin and a wallet. You'll only need a wallet because you are earning the Bitcoins! Custodial Wallets like the [Wallet of Satoshi](https://www.walletofsatoshi.com/) or [blue wallet](https://bluewallet.io/) are a good start, but eventually you'll want to create yourself a setup that's more secure. Always remember the wise words of the experienced Bitcoiners: *"Not Your Keys, Not Your Bitcoin. Not Your Node, Not Your Rules."*

= If I deactivate the Ice Dragon plugin, will I lose my configuration? =

No. You can deactivate the Ice Dragon plugin at any time without losing any configuration data.

= What can I do if something does not work as intended? =

Please don't hesitate to reach out to us. This is still an early-day implementation and we are happy to hear where the obstacles are and help you out with any issue.
Just write an e-mail to lightning@puzzle.ch .

== Changelog ==

= 0.0.3 Alpha =
* Better sanitizing of input data
* Major JWT library update from 0.1.0 to 1.0.0
* Code cleanup

= 0.0.2 Alpha =
* Fixes to match the needs of WorPress.org plugin store
* Move ice-dragon.ch integration part to own section plugin settings
* Removal of unneeded Leaky Paywall code

= 0.0.1 Alpha =
* Initial Release based on a Fork of ZEEN101's Leaky Paywall

== License ==

Ice Dragon for WordPress
Copyright (C) 2019 Puzzle ITC.
Based on [ZEEN101](https://zeen101.com/)'s [Leaky Paywall](https://wordpress.org/plugins/leaky-paywall/#description).

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.

