# petal's filter lists!

**A little collection of a few small filter lists by yours truly, mostly based off of my own browsing experiences.** Don't expect your entire life to change using these, of course; I'm just yet another maintainer of a tiny filter list that no one uses. I hope you find them useful though! Aimed for use with [uBlock Origin](https://ublockorigin.com); if you aren't using this, then **don't bother**.

You can report any breakage or suggest sites to target in the [issue tracker](../../issues). However, do note that if you report issues with blocking extensions other than uBO, then I won't do anything about them.

Everything here is licensed under GPLv3! https://www.gnu.org/licenses/gpl-3.0.en.html

**Doots** - [subscribe](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/strayPetal/filter-lists/main/doots.txt&title=Doots)\
_Small, but potent privacy-centric blocklist._\
Doots has a few things going for it: there are some generic filters that block common tracking mechanisms that EasyPrivacy doesn't include, and some generally unnecessary connections. **Where Doots really shines is in its site-specific filters.** Basically, for a couple sites, it'll employ a few filters that work for that site only, blocking out most of the noise and leaving in only what's necessary. It's sort of like dynamic filtering, except it allows for more granularity** (cause you can't block by URL path or for most request types with uBO's actual dynamic filtering) and it's preconfigured, at least for the sites I put on there. _At the moment, you'll notice the most difference on Google sites._ A couple `removeparam` filters are also included.