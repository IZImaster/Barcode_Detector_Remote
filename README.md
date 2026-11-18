# Barcode Detector Remote

Laptop page for the **Barcode Detector** Android app. It connects to the device over Bluetooth LE (Web Bluetooth) in **Google Chrome** or **Microsoft Edge**, with nothing to install.

**Open it:** https://izimaster.github.io/Barcode_Detector_Remote/

It is a single self-contained file (`index.html`): you can also save it and open it offline. Chrome may then ask you to choose the device each time.

## What it does

- Shows the last scanned barcode or QR code live, with a **Copy** button.
- Detector and Objects notes: view, add, edit (text, title, colour), switch on/off, copy between tabs, delete.
- Searches the device's scan log (the search runs on the device).
- **Find device** (⚙ Settings): the device rings at full volume, vibrates and flashes its light.
- **Left-behind alarm** (⚙ Settings): the laptop beeps when the signal is weaker than a set dBm for a set number of seconds. Stop it on the laptop or on the device.

To try it without a device, add `?demo` to the address or use ⚙ Settings → Demo.

## On the device

Barcode Detector → Settings (PIN) → **Laptop link** → switch on "Bluetooth link to laptop". An optional link password can be set there; enter the same password in this page's ⚙ Settings.
