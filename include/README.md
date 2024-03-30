_**NOTE**: these lists aren't made to be imported directly! These are the lists that make up the main filter lists in the root folder of this repository._

`[number][letter]` lists are aimed primarily towards blocking on specific sites.

Number indicates how hard the list blocks.
- `1` - block any red flags or simple things not needed for core functionality.
- `2` - block everything on a site by default, and then create exceptions for things needed.

Lists with the same letter - whichever has a higher number will block more aggressively, so the lower number one will be redundant.
- `a` - only a few rules needed to achieve default-deny functionality per site. e.g. Bilibili
- `b` - large amount of rules needed to achieve default-deny functionality per site. e.g. Google Suite