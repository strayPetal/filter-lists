# internal lists
_**NOTE**: these lists aren't made to be imported directly! These are the lists that make up the main filter lists in the root folder of this repository._

`[letter][number]` lists are aimed primarily towards blocking on specific sites.

Number indicates how hard the list blocks.
- `1` - block any red flags or simple things not needed for core functionality.
- `2` - block everything by default, and create exceptions per domain or request type. May let some stragglers through if it means less filters, but not as much as `1`.
- `3` - block everything by default, and allow through only what is strictly necessary.

In the graphic below, "optimal" means that not many rules are required on the sites targeted to achieve that level of blocking. "Overkill" means that an absurd amount of rules is required to achieve that level of blocking. There is no point blocking less than the optimal level, so "no point" lists just don't exist.

![](list-aggressiveness.png)