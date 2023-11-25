This is a no-datastore, client-side paste service.  It turns text into [LZMA](https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Markov_chain_algorithm)-compressed, [Base64](https://en.wikipedia.org/wiki/Base64)-encoded URLs.

Because the entire paste is inside the URL, there's no risk of losing your data because a 3rd-party service vanished or deleted old pastes. If you have the URL, you have the pasted data.

This fork of <https://topaz.github.io/paste/> with several changes to make it appropriate for sharing poetry or prose:

* Uses a non-monospaced font
* Centers content on the page; horizontal centering is based on the width of the longest line
* Defaults to light color scheme

All content is plain text (no formatting). I may add some light formatting and color capabilities in the future that carry with the generated URL.