# dither-sink

One static HTML page (a dithered boat scene, drag the light). Served by python3 http.server as the home-server user service `dither-sink.service` on 127.0.0.1:4020, behind the cjdex gate at dither.cjdex.net.

Source: `public/index.html` (single file, no build).

## Copyright and origin

Licensed under the 0BSD license. See [LICENSE](LICENSE).

Inspired by an app seen on Instagram. This version is a separate build, not a copy of that app. Differences:

- Adds a real-time clock: the scene follows the actual time of day.
- Layout scales to the screen size (clamp() and container units).
- Less polished than the Instagram original: its 3D rendering and birds look better than this version's.
