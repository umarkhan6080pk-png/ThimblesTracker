ThimblesTracker prototype

1. Open index.html in Chrome on Android or in a desktop browser.
2. Select a recorded thimbles-game video.
3. Press Analyze video.
4. The prototype looks for compact bright-red blobs and labels their horizontal position.

This is an early proof of concept, not a finished APK and not a guaranteed tracker.
It does not infer the ball's location while it is fully hidden under a cup.
To publish as an Android APK, this web prototype must be wrapped in an Android WebView
project and tested on multiple recordings. The current prototype analyzes local video
in the browser and does not upload it to a server.
