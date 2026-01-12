# firefox-browser-extension

This is the initial configuration after following the [Mozilla Developer's Guide](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_second_WebExtension).

Important note for FireFox linux users, the browser extension development doesn't work with `web-ext run`
if FireFox is installed from a snap. In which case one should manually put the main js `ffextension.js` in the `about:debugging` -> `This FireFox` then select `ffextension.js`.
