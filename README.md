# ANKI PWA starter

This package is a Progressive Web App (PWA) starter based on the current interactive ANKI prototype.

## Install on iPhone
1. Upload the contents of this folder to a static HTTPS host (for example, a static site host).
2. Open the hosted `index.html` in Safari on the iPhone.
3. Tap Share → Add to Home Screen.
4. Name it `Anki`, then tap Add.

A local ZIP or `file://` HTML page cannot be installed directly as a Home Screen web app; it must be hosted over HTTPS.

## Important limitations
This is still a front-end prototype. It does not have real accounts, cloud messaging, real-time voice rooms, push notifications, or native game-audio mixing. A PWA cannot reliably mix microphone voice with another game's audio on iOS. Those features need a backend, a real-time voice service, and native iOS/Android work.

## Native iOS app
For an App Store/TestFlight native app, you will need an iOS build pipeline (usually Xcode on a Mac or a cloud macOS build service) and an Apple Developer account for distribution. The PWA route is the fastest way to get an icon on your Home Screen while developing.
