# Fun Laser
_A rather aggressive blocklist for the sites I frequent. As a laser, its efforts are quite concentrated on select sites, but it does nothing for those that aren't in the line of fire._

This list will only block stuff on a few select sites that I frequently visit, so absolutely nothing gets blocked on sites that aren't targeted. However, on the sites that _are_ targeted, it will aim to block _as much as possible_ while still maintaining essential functionality. Do note that _my_ idea of "essential functionality" will probably differ from _your_ idea of "essential functionality." This list performs on a sort of _block everything by default and only allow the essential stuff_ kind of idea.

Since static filtering allows for more granular control over requests than dynamic filtering does, this will probably block harder than uBO medium/hard mode does, on targeted sites.

For example, for [Bilibili](https://www.bilibili.com), a popular Chinese video streaming site, this list has two rules:

```
*$from=bilibili.com,to=~akamaized.net|~akamai.net
@@||hdslb.com/bfs/static/player/$from=bilibili.com,script
```

The first rule will block everything coming from `bilibili.com` except if the destination is to `akamized.net` or `akamai.net` (some video decoding thing or something, I don't know exactly). Because of the way uBO works, the main document won't be blocked by this rule.

The second rule creates an exception for scripts required for the video player to function. Everything else from `hdslb.com` will continue to be blocked, including a few major red flags like a script named `https://s1.hdslb.com/bfs/seed/jinkela/short/user-fingerprint/bili-user-fingerprint.min.js` that isn't (currently) being blocked by the default lists.

_It's also extremely funny how you can block every single request from `bilibili.com` and all of its subdomains except to load the main document, and the video player will still function perfectly fine._

Also do check out the [LibRedirect](https://libredirect.github.io) extension! It can redirect a lot of sites to more privacy-friendly frontends, so creating rules for Reddit, for example, is entirely unnecessary if you only view content through [Redlib](https://github.com/redlib-org/redlib), for example.