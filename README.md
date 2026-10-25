# Lexicon (the old website)

This address used to serve the original Lexicon website. It now shows one notice pointing to the
Lexicon app on the App Store. The site's code is not public.

There is deliberately no `index.html` and no `sw.js`: GitHub Pages serves `404.html` for every
address here, with a 404 status. The old website kept an offline copy of itself in visitors'
browsers and replaces that copy only with a successful page, so a 404 leaves it (and the progress
saved next to it) as it was. Adding an `index.html` or a `sw.js` here would change that.
