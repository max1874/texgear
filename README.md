# Texgear

Texgear forwards the text messages your Android phone receives to your iPhone and Mac, so verification codes arrive where you are working. Messages are end-to-end encrypted on the phone; the relay in between only ever handles ciphertext.

This repository hosts the downloads. Source code is not published here.

## Download

| Platform | Get it | Status |
| --- | --- | --- |
| Mac | [Releases](https://github.com/max1874/texgear/releases) → `Texgear-<version>.dmg` | Available |
| Android | — | Not yet available |
| iPhone | — | In testing, not yet on the App Store |

The Mac app is signed with Developer ID and notarized by Apple. Each release lists the SHA-256 of its disk image; check it with `shasum -a 256 Texgear-<version>.dmg`.

## Requirements (Mac)

- macOS 15 or later, Apple silicon or Intel.
- An Android phone running Texgear, which sends the messages.
- An iPhone running Texgear, signed in to the same Apple Account, to finish setting up the Mac. A Mac cannot yet prove to the relay that it runs a genuine copy of the app, so the iPhone vouches for it once over iCloud.
