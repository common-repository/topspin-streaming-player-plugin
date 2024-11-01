=== Topspin Streaming Player ===

Contributors: fraxture
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CDV95SG2YQXXY  
Tags: Topspin,music,streaming player, widget  
Tested up to: 3.4.1  
Requires at least: 3.0.2  
Version: 0.1  
Stable Tag: 0.1  
License: GPLv2  
License URI: http://www.gnu.org/licenses/gpl-2.0.html  

== Description ==

## **Description**

This plugin adds a widget for displaying a [Topspin](http://topspinmedia.com) streaming player to the widget areas on your site. In order to use this plugin, you will need to set up an account with Topspin.

## **Live Examples**

[http://okgo.net](http://okgo.net/) - Streaming player widget used on the front page.

## **Feedback & Donations**

Please remember to rate this plugin. If you have comments, critique, or suggestions either send an email to emiller@screen-cuts.com or leave feed back in the support forum here.

If you like this plugin, please consider [donating](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CDV95SG2YQXXY ). It will lead to further improvements. 

== Installation == 

## **Installing the Plugin**

1. First, this plugin is designed to work with Topspin, so you'll need a topspin account. Visit [topspinmedia.com](http://topspinmedia.com) to open an account.

2. Once you've created an account, install the plugin in your Wordpress site by either installing the plugin through wordpress's automatic installation pages, or by
uploading the 'topspin-streaming-player' folder to your plugins directory (i.e. /yoursite/wp-content/plugins).

3. Active the plugin in the Wordpress Plugins Dashboard.

## **Using the Topspin Streaming Player Widget**

1. Activate Widget

Once you've installed and actived the plugin, the Topsin Streaming Player Widget will be available in the widgets page of your Wordpress installation. In order to 
enable an instance of the widget simply drag into one of your widget areas, as you would any other Wordpress widget. 

2. Set the Topspin widget ID

In order to specify, which streaming player you want to load into your widget, you will then need the widget ID that Topspin assigns to each Streaming Player.  If
you have not already created any streaming player widgets, you will need to do so within the [Topspin App](http://app.topspin.net). After setting up the streaming 
player within Topspin, find the Widget ID for the player. The widget ID can be found in the embed code for each widget. Here is an example of the embed code with 
the widget ID in bold: 

> `<iframe id="tsFrame127019" src="http://cdn.topspin.net/api/v3/player/`**127019**`" frameborder="0" width="234" height="226" ></iframe>`


3. Choose the Topspin Streaming Player Version

As of July 2012, Topspin has three available version of their streaming player. The default version--ie the version provided in the embed code within the Topspin
App--is Version 3. Each of these versions have a different look and feel and also different customization options. You will need to select which version you want
to display. 

*Note: If you select Version 1, you will also need to provide the Artist ID, which can be found within the [Topspin App](http://app.topspin.net).*

4. Set the Width and Height of the Streaming Player

In order to get the streaming player to fit correctly into the widget area on your website, you may need to set the width and height of the player, which you are 
able to do for each version of the player. 

5. Additional Customization?

Customization for the Topspin Streaming Players is handled differently for each version -- by Topspin's design. 

**Version 1** - No customization possible at the moment. This may be added to future versions of this plugin.

**Version 2** - Customization of Version 2 of the Topspin Streaming Player is possible within this plugin. For this, you'll need to go to the Settings Page for the
                Topspin Streaming Player Plugin (Settings->Topspin Player). There you'll find editable CSS styles with a description of what part of the Version 2 
                player each style impacts. This will likely take some trial and error to get right. 

**Version 3** - Customization for Version 3 of the streaming player must be handled within the [Topspin App](http://app.topspin.net).

== Frequently Asked Questions ==

= Do I need a Topspin account to use this plugin? =

Yes. Go to [topspinmedia.com](http://topspinmedia.com) to set one up.

== Screenshots ==
1. Widget Interface
2. Player Version One
3. Player Version Two
4. Player Version Three

== Changelog ==

== Upgrade Notice == 

Upgrade via Wordpress.