## Overview

Discord-Chrome-Presence allows you to set your Discord Rich Presence to whatever you're looking at it in Chrome. An addition, the Chrome extension is included in order to relay site info.

## Installation

```
git clone https://github.com/jczstudios/discord-chrome-presence
npm install
npm start
```
Then, install the Chrome extension from the extensions page directly.

## Usage
Install the Chrome extension, included in the extension directory. Then, start the Node server using
```
npm start
```
At this point, Discord will need to be open. For now, your presence updates only when the active tab is updated [Chrome tabs API](https://developer.chrome.com/extensions/tabs#event-onUpdated). For example, refreshing the page, navigation, etc.

## License

[Unlicense](http://unlicense.org/)
