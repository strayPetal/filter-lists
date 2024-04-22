# internal lists
_**NOTE**: these lists aren't made to be imported directly! These are the lists that make up the main filter lists in the root folder of this repository._

`[number][letter]` lists are aimed primarily towards blocking on specific sites.

Number indicates how hard the list blocks.
- `1` - block any red flags or simple things not needed for core functionality.
- `2` - block everything by default, and create exceptions per domain or request type.
- `3` - block everything by default, and create many, very focused exceptions.

Letter indicates how easy it is to achieve different levels of blocking. One level will be optimal (i.e. effective blocking of important stuff without an absurd amount of filters) for different sites. If trying to block more aggressively, it'll need a lot more rules.
- `a` - optimal on `3`.
- `b` - difficult to achieve `3`, so optimal on `2`.
- `c` - difficult to achieve `2`, so optimal on `1`.

Optimal lists are `3a`, `2b`, and `1c`. Doots (the recommended list) uses these three.

`1a`, `2a`, and `1b` are not used, since there's no point in blocking less than the optimal lists.