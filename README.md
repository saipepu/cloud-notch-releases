# Cloud Notch

Cloud Notch lives in your MacBook's notch and shows which Claude Code session needs you. Allow a command, answer a question or approve a plan without switching windows.

This repository holds the downloads and the release history. The app's source is not published here.

## Download

**[Download the latest version](https://github.com/saipepu/cloud-notch-releases/releases/latest/download/CloudNotch.dmg)**, or pick an earlier one from [Releases](https://github.com/saipepu/cloud-notch-releases/releases).

Requires macOS 15.6 or later, on Apple silicon or Intel, and Claude Code.

## Install

1. Open `CloudNotch.dmg`.
2. Drag Cloud Notch to Applications.
3. Open it. Answering from the notch takes one setup command, which you copy from Settings and paste into Terminal.

The disk image is signed with a Developer ID and notarized by Apple, so it opens without a warning.

## Updates

Once a day the app checks this repository for a newer version. When one is out, a blue arrow appears in the notch's tab bar, and Settings → General shows what is new with a Download button. Nothing is installed for you, and the check can be switched off.

## What is in this repository

| | |
| --- | --- |
| [Releases](https://github.com/saipepu/cloud-notch-releases/releases) | Every version as a disk image, with its release notes |
| `releases.json` | The feed the app reads to learn that a newer version exists. It is written by the release process; please don't edit it by hand |

Every version number is used once. A version that had to be withdrawn is marked as such in its release notes, and a fixed release follows under the next number.

## Feedback

Questions and bug reports: open an [issue](https://github.com/saipepu/cloud-notch-releases/issues).
