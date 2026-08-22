# Aura Trade OS

Prebuilt Aura Trade OS browser extensions for Chrome and Firefox.

Download the Chrome or Firefox archive from the
[latest release](https://github.com/in-aura-we-trade/aura_extension/releases/latest). Only
install packages published in this repository.

## Chrome

1. Download `aura-trade-v0.0.13-chrome.zip` from the latest release.
2. Extract the archive to a permanent directory.
3. Open `chrome://extensions`.
4. Enable **Developer mode**.
5. Select **Load unpacked**.
6. Select the extracted directory containing `manifest.json`.

Keep the extracted directory after installation. Chrome loads the extension
directly from that directory.

## Firefox

1. Download `aura-trade-v0.0.13-firefox.zip` from the latest release.
2. Extract the archive.
3. Open `about:debugging#/runtime/this-firefox`.
4. Select **Load Temporary Add-on**.
5. Select `manifest.json` in the extracted directory.

Firefox removes temporary add-ons when the browser exits. This package is
intended for temporary developer installation. Persistent installation in
standard Firefox requires a Mozilla-signed package.

## Updating

### Chrome

1. Download and extract the new Chrome archive.
2. Open `chrome://extensions`.
3. Remove the previous Aura Trade OS installation.
4. Select **Load unpacked** and choose the new extracted directory.

### Firefox

Load the new `manifest.json` from
`about:debugging#/runtime/this-firefox`. Temporary extensions must be loaded
again after Firefox restarts.

## Uninstalling

- Chrome: open `chrome://extensions` and select **Remove** on Aura Trade OS.
- Firefox: open `about:addons`, locate Aura Trade OS, and select **Remove**.

## Troubleshooting

- Make sure the archive was extracted before selecting `manifest.json`.
- On Chrome, select the directory that directly contains `manifest.json`.
- Reload the extension after replacing any files in its extracted directory.
- If a site was already open during installation, reload that site.
