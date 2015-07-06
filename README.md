:do_not_litter: Fritz!Box Blacklist
===================================

A list of domains to be blocked in my Fritz!Box.

This project is meant to help some companies to see the benefits of HTTPS. :smiley:

Instructions
------------

Short instructions:

1. See [AVM's instructions on how to setup a blacklist in your Fritz!Box](http://avm.de/nc/service/fritzbox/fritzbox-7390/wissensdatenbank/publication/show/8_Internetnutzung-mit-Kindersicherung-einschraenken/)
2. Copy contents of [fritzbox-blacklist.txt](https://raw.githubusercontent.com/fboes/fritzbox-blacklist/master/fritzbox-blacklist.txt) to your Fritz!Box' blacklist
3. Be sure to check if HTTPS traffic is still allowed

This will work with a standard firmware.

There is also an [extended instruction on how to set up your Fritz!Box as an AdBlocker](http://blog.3960.org/post/123040268295/fritz-box-als-adblocker) (German).

Development
-----------

There is a maximum of 500 entries for this blacklist. Choose each entry wisely.

Put each domain in a single line. Do not enter comments or anything else.

E.g.: To block `http://ads.example.com/some_script.js` enter `ads.example.com` or just `example.com`. `example.com` will also block all files from `www.example.com` and any other subdomain.

On the structure of URLs for this blacklist consult [AVM's documentation for blacklists](http://service.avm.de/help/de/FRITZ-Box-Fon-WLAN-7490/014/hilfe_internet_filter_blacklist). Keep in mind to keep this list as simple as possible, to keep it useful for other routers as well.

Legal stuff
-----------

Author: [Frank Boës](http://3960.org)

Copyright & license: See LICENSE.txt

These instructions are NOT affiliated with, endorsed, or sponsored by AVM.
