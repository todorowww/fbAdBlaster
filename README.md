# Facebook Ad Blaster

This extension removes sponsored posts from users Facebook news feed.

NOTE: This extension in no way interacts with ads on the right, which Facebook hasn't
attempt to make impossible to block, only those in the news feed.

# Update History

###v1.0
- Initial version, forked, and altered to remove ads, instead of blocking them

# Code Overview

- *manifest.json* contains information about the overall structure of the extension as well as the title, version number, and description.
- *popup* is just a simple description of the extension that appears when the user clicks the icon in the upper right.
- *ad_remover.js* is the script that runs on facebook.com, searches for ads, and highlights them.
- *locale_info.js* keeps information about the "Sponsored" text in various languages to support all Facebook locales.
- *externalCode* contains jQuery 1.12.4

# Running This Extension

Note that this is Chrome/Chromium only extension. At the moment, this extension is not available on Chrome Web Store, with no immediate plans on making it available.

To get this extension running from source code, follow these steps:

[Download latest ZIP archive](https://github.com/todorowww/fbAdBlaster/archive/master.zip)

- navigate to "chrome://extensions"
- click the checkbox next to "Developer mode" in the upper right hand corner
- click the "Load unpacked extension..." button below the "Extensions" title
- select the fbAdKBlaster folder from your filesystem
- refresh any open Facebook pages

# Credits and attributions

Forked from [fbAdHighlighter](https://github.com/storey/fbAdHighlighter) by [Grant Storey](https://github.com/storey).

Icon made by [OCHA](http://www.flaticon.com/authors/ocha) from [www.flaticon.com](http://www.flaticon.com).

### License:
MIT
