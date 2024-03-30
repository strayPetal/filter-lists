# filter lists!

A little collection of a few small filter lists by yours truly, mostly based off of my own browsing experiences. Don't expect too much from them, of course; I'm just keeping these up to date as I please, and won't attempt to actively maintain them (unless of course it breaks something for me), though I will do my best to keep up with any issues if you put them in the [issue tracker](../../issues). No promises though!

Primarily aimed for use with [uBlock Origin](https://ublockorigin.com).

Everything here is licensed under GPLv3! https://www.gnu.org/licenses/gpl-3.0.en.html

## Network blocking lists
### Privacy, bloat, URL params, etc
Increase privacy, kill unnecessary connections, and the like. Ordered from least to most aggressive. I would recommend **Doots** for most people. **Only import one!**\
_Also, some tracking URL params that aren't covered in other mainstream lists (so uBO default lists and [DandelionSprout's "Legitimate URL Shortener"](https://github.com/DandelionSprout/adfilt/discussions/163)) will be included in all of the following lists, at least until I can suggest for them to be added to Legit URL Shortener._

**Doots Lite** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/doots-lite.txt&title=Doots%20Lite)\
_Lighter version of my Doots list. Will break less stuff, but block significantly less hard._\
Blocks any red flags that I stumble upon in the Logger while browsing.

**Doots** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/doots.txt&title=Doots)\
_Small, but potent privacy-centric blocklist._\
Same as above, but where it's reasonable (i.e. you don't need a truckload of rules), it will use a default-deny approach to sites, meaning it will block everything from that site by default and only allow what's needed for the core functionality of the site.

**Fun Laser** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/fun-laser.txt&title=Fun%20Laser)\
_A rather aggressive blocklist for the sites I frequent. As a laser, its efforts are quite concentrated on select sites, but it does nothing for those that aren't in the line of fire._\
Default-deny approach on all sites targeted, even those that need a large amount of reallowing to function.