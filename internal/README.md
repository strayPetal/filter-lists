# Internal lists
_**NOTE**: these lists aren't made to be imported directly! These are the lists that make up the main filter lists in the root folder of this repository._

## Site-specific lists
`[letter][number]`. Lists designed to block more aggressively on select sites.

Number indicates how hard the list blocks.
- `1` - block any red flags or simple things not needed for core functionality.
- `2` - block everything by default, with exceptions per domain or request type. Will let some stragglers through if it means less filters than if using the `3` approach.
- `3` - block everything by default, and allow through only what is strictly necessary.

In the graphic below, "optimal" means using a reasonable amount of filters to achieve that blocking level. "Overkill" means that an unreasonable amount of filters are required. There is no point blocking less than what is optimal, so "no point" lists just don't exist.

![](list-aggressiveness.png)