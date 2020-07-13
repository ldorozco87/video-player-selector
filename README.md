# Gilead Video Player Selector
This repository have 2 approaches:
- Using video.js library
- Using a custom player

## Get started
- npm install, to install all node_modules dependencies
- npm start, to open a local server using browser-sync (it has live reload watching all files)
- npm run transpile-vidjs, transpile JS for the video-js-player using babel for older browsers, outputh: videoJSPlayer.js
- npm run transpile-custom, transpile JS for the video-js-player using babel for older browsers, outputh: customVideoPlayer.js

### Adding node-sass support from NPM (Work-In-Progress)

#### NOTES: 
- To lazy to wrap this on Webpack lol, this project eventually will have Webpack
- Use the "assets" folder for any video, transcript, poster, and images
