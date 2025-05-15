# Ad Blocker

Built a Chrome extension that blocks requests to a predefined list of common advertising and tracking domains.

## Functionality

The extension works by intercepting network requests made by your browser and canceling those that match the domains listed in its internal filter list.

The current filter list includes domains such as:

* `*.doubleclick.net`
* `partner.googleadservices.com`
* `*.googlesyndication.com`
* `*.google-analytics.com`
* `creative.ak.fbcdn.net`
* `*.adbrite.com`
* `*.exponential.com`
* `*.quantserve.com`
* `*.scorecardresearch.com`
* `*.zedo.com`
* `*adaway.org/h*`
* `*v.firebog.net/*`
* `*s3.amazonaws.com/*`

## Installation

1.  Download or clone this repository.
2.  Open Google Chrome.
3.  Navigate to `chrome://extensions/`.
4.  Enable "Developer mode" in the top right corner.
5.  Click the "Load unpacked" button in the top left corner.
6.  Select the directory containing the extension files (including `manifest.json` and `background.js`).

The extension should now be installed and active. You should see its icon in your browser's toolbar.

## Usage

Once installed, the ad blocker will automatically start blocking requests to the listed domains as you browse the web. There is no user interface for this basic version.

## Limitations

* This is a very basic ad blocker with a static list of filters.
* It does not support whitelisting or custom filter lists.
* It does not perform cosmetic filtering (hiding ad containers).
* Updates to the filter list require updating the extension itself.

## Contributing

This is a simple project for demonstration purposes. Contributions for expanding its functionality (like adding options for whitelisting or importing filter lists) are welcome!
