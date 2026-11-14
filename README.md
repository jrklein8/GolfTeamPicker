# Farmer's Invitational

A one-page captain picker for the golf trip. Enter two to eight names and let luck decide.

- **Cart race:** carts race down a 600-yard par 5 through cart girl boosts and hazards. The first two to the green are the captains.
- **Par 3 shootout:** one swing each at a 150-yard par 3. The two closest to the pin are the captains.
- **Save video:** every run is recorded in the browser and can be saved as an MP4 with the music.

## Run it

The site is plain static files. Open `index.html` through any web server, or publish the repository with GitHub Pages (Settings > Pages > Deploy from a branch > `main`, folder `/`).

## Files

- `index.html`: the whole page (markup, styles and script).
- `girls/`: photos shown on cart girl boosts.
- `music/`: the two background tracks, plus AAC copies used for the saved video.
- `lib/mp4-muxer.js`: the MP4 writer ([mp4-muxer](https://github.com/Vanilagy/mp4-muxer), MIT licence).
