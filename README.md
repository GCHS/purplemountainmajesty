# Purple Mountain Majesty
Purple Mountain Majesty is the Ghost theme used on https://giancarlosaraceni.com.

It is intended to be:
1. Dark
2. Purple
3. Out of your way

"Dark" and "purple" are accomplished via color palette. "Out of your way" is achieved by putting as much text onscreen as is comfortable and using the default sans-serif proportial font of the user to minimize font accent.

In addition, as a heavy user (and abuser) of parentheticals, footnotes are pulled out from their own separate section at the actual foot of the page and inline, via in-page popups, where I feel them to be more contextful.

The footnotes are created client-side after page load, as otherwise recursive footnote structures (remember that parenthetical abuse?) would result in a page of infinite size (and infinite rendering time!). Highest-level footnotes are generated in a single pass, the rest are generated on-demand (when first clicked or tapped).
