# rodrigoleles.com

Static mirror of the portfolio built in Framer
(source: https://adored-expectations-761785.framer.app/), generated with
[framer-to-code](https://github.com/iamshubhransh/framer-to-code).

Everything (pages, images, videos, fonts, the Framer runtime) is served from this
repo, with no build step. The only external requests are two Lottie animations on the
home page, loaded from `cdn.lottielab.com`.

- Preview locally: `node server.mjs`, then open http://localhost:4178
- Must be served from the domain root (Framer's runtime requests `/images/…`, `/videos/…`).
- Re-sync after editing in Framer: re-run the skill's `crawl.mjs` + `build.mjs` against the Framer URL.
