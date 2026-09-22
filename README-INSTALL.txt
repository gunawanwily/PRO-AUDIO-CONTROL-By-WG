PRO-AUDIO-CONTROL — UNIVERSAL PWA
====================================

This package is the installable web-app version of the current dashboard.

Supported installation targets:
- Android phone
- Android tablet
- Windows PC
- iPhone / iPad (Safari Add to Home Screen)
- Other modern browsers that support PWA installation

The existing dashboard/layout and audio functions are kept in index.html.
The PWA manifest enables portrait/landscape behavior and standalone launch.
The service worker enables offline loading of the app shell after first load.

IMPORTANT:
- Audio files selected by the user remain local to the device/browser.
- Browser codec support varies; MP3/WAV are generally the safest.
- For installation, the PWA must normally be served from HTTPS (or localhost during development).
- On iPhone/iPad: open the HTTPS address in Safari -> Share -> Add to Home Screen.
- On Android/Windows: open the HTTPS address in a supported browser -> Install/Add to Home Screen.
