Handsfree scrolling chrome extensions, #lauzhack.

#### File Structure

_content_script.js_ is injected into every webpage, in order to
interact with the webpage (to scroll and run eye tracker)

_main.js_ is the "background page" that loads the extension,
registering the onclick event of the extension's icon (upper right)

_options.html_ is the options page. It has access to
```chrome.storage``` in order to update the app's configuration.
