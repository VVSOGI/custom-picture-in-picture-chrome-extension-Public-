# Picture-in-Picture-From-Korea Chrome Extension

Get it on the Chrome Web Store at (https://chromewebstore.google.com/detail/picture-in-picture-from-k/ohmhbgphjbplnmoflfenimhadficecoo)

A simple Chrome Extension to demonstrate the [Picture-in-Picture Web API](https://wicg.github.io/picture-in-picture/) in Chrome.

<img width="1440" alt="스크린샷 2024-10-19 오후 4 33 13" src="https://github.com/user-attachments/assets/f35fe035-52bb-4ca7-bab7-8a889011ad1c">

origin repository -> [picture-in-picture-chrome-extension](https://github.com/GoogleChromeLabs/picture-in-picture-chrome-extension)

## New in this custom release

<img width="1440" src="https://github.com/user-attachments/assets/f5b7c392-fdfa-45a6-a837-167f1e81abd6">

The existing picture-in-picture-chrome-extension can only be switched on the tab where the initial video was played in PIP mode, but the Picture-in-Picture-From-Korea can switch PIP videos on other tabs using shortcuts.

## Configuration

The keyboard shortcut

```json
    "_execute_action": {
      "suggested_key": {
        "windows": "Alt+P",
        "mac": "Alt+P",
        "chromeos": "Alt+P",
        "linux": "Alt+P"
      }
    },
```

The keyboard shortcut can be changed on the
Chrome Extension Shortcuts settings page:
chrome://extensions/shortcuts

## How to use

1. git clone [this-repo]
2. move to url -> chrome://extensions/shortcuts
3. Turn on Developer mode in the upper-right corner.
4. Click button that Load the extracted extension in the upper-left corner.
5. Select the folder where your manifest.json is located
6. Use it as you would with the picture-in-picture-chrome-extension.

## Why did you create it?

My brother and I are both currently looking for jobs, so we program together and study together. However, I often want to watch YouTube videos while studying or working, but I don't want to get caught by my brother, so I thought I needed a way to quickly switch between them.

## Caution

Switching will not work if the last touched part of the Chrome browser when switching is a PIP Video. Presumably this is because the PIP Video is not recognized as a tab, even though it is part of the Chrome browser.

## Recommandations

I'm looking for job so it doesn't matter to me, but for those of you who are working, I don't recommend using this feature to watch YouTube videos at work.

## Issue

1. If you have an extension that uses the Alt + P, Option + P shortcut before this, you'll need to reset it in the shortcut settings to make it work.
