# petal's filter lists!

**A little collection of a few small filter lists by yours truly, mostly based off of my own browsing experiences.** Don't expect too much from them, of course; I'm just updating these whenever I wish. Aimed for use with [uBlock Origin](https://ublockorigin.com); if you aren't using this, then **don't bother**.

You can report any breakage or suggest sites to target in the [issue tracker](../../issues). However, do note that if you report issues with blocking extensions other than uBO, then I won't do anything about them.

Everything here is licensed under GPLv3! https://www.gnu.org/licenses/gpl-3.0.en.html

## Network blocking lists
### Privacy, bloat, etc
Increase privacy, kill unnecessary connections, and the like. Ordered from least to most aggressive. I would recommend **Doots** for most people. **Only import one!**

**Generic** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/generic.txt&title=Generic)\
_Generic privacy-centric filters to supplement default uBO lists._\
Traditional filter list for a few things that aren't covered by the default uBO lists. Ideal if you don't ever visit the "complex" sites that the below lists target more aggressively.

**Doots** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/doots.txt&title=Doots)\
_Small, but potent privacy-centric blocklist._\
Uses the Generic list above, but will also employ specialised rules for certain "complex" sites (i.e. sites that aren't just news articles, which you can just use hard mode + no scripting on), which cleans up connections that can slip through due to dynamic filtering's limited granularity. With this "site-specific" approach, Doots aims for an optimal amount of filters.

**Fun Laser** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/fun-laser.txt&title=Fun%20Laser)\
_A rather aggressive blocklist for the sites I frequent. As a laser, its efforts are quite concentrated on select sites, but it does nothing for those that aren't in the line of fire._\
Same as Doots, except that it will use as many filters as necessary to only allow through what is strictly necessary in the "site-specific" approach. In most scenarios, there is not much benefit to using this over Doots other than that it makes you feel cooler because you're blocking more.

### URL cleaning
**Param Waiting List** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/param-waiting-list.txt&title=Param%20Waiting%20List)\
_Generic URL param cleaning list, covering anything I find that isn't covered by DandelionSprout's "Legitimate URL Shortener". Some are here permanently, while others are just waiting here until I eventually suggest their addition into that list._