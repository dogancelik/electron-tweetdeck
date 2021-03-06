<img src="https://cloud.githubusercontent.com/assets/486818/12889894/c893d2c8-ce89-11e5-9e0f-1411a9c87eec.jpg" height="330" alt="Atomic TweetDeck">

**Atomic TweetDeck** is just a small [Electron](http://electron.atom.io/) TweetDeck app.

* No modifications, just a web window.
* Made specifically for Windows.
* Double click Tray to show window, right click opens a menu.
* <kbd>Ctrl+Q</kbd> closes app, <kbd>Ctrl+W</kbd> hides window, <kbd>Ctrl+R</kbd> reloads page.
* Minimize *or* close to hide to tray.
* Copy page, link or image address to clipboard with right click menu.

## Download

[Download the latest binary package](https://github.com/dogancelik/atomic-tweetdeck/releases/latest)

## Build

You can build the source with *electron-packager*:

You can customize the build process by modifying `buildArch`, `buildPlatform`, `zipTargets` in [package.json](package.json).

```sh
npm run clean
npm run build
```

To zip the builds, you need the 7-Zip binary `7za`.

To download the binary, you can use the NPM package `7zip-bin`
or download the binary manually from [the official website](https://www.7-zip.org/download.html).
If you use the NPM package, you need to add to your `$PATH` manually.

```sh
npm run zip
```

or you can just start with *electron*:

```sh
npm run start
```
