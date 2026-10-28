# Basement TV

A retro basement TV experience with three channels, an interactive remote, a TV guide, and synchronized playback.

## Run locally

Serve this folder with any static HTTP server, for example:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000/ in a browser. Video playback requires internet access because the test films are hosted externally. The TV guide describes the current test lineup; each channel loops its test film.

The page is static and can be hosted by GitHub Pages or another static host. No build step or server-side secrets are required for the current version.
