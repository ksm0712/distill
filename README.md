# Distill

A Chrome extension that instantly explains anything on your screen using Claude.

## What it does

Distill lets you explain any content on your screen without leaving your browser. Click the extension icon, and Distill will screenshot your current tab and send it to Claude with your custom prompt — giving you a clean, simple explanation in seconds.

- No API key required — works with your existing Claude Pro account
- Custom prompt support — set your explanation style once, use it forever
- Session aware — continues your conversation or starts fresh with New Topic

## How to install

Distill is not yet on the Chrome Web Store. To install it manually:

1. Download or clone this repository
2. Open Chrome and go to `chrome://extensions`
3. Enable **Developer Mode** in the top right
4. Click **Load Unpacked**
5. Select the `distill` folder

The Distill icon will appear in your Chrome toolbar.

## How to use

1. Navigate to any page you want explained
2. Click the Distill icon in your toolbar
3. Optionally set a custom prompt (saved automatically)
4. Click **Explain This**
5. Claude will open and explain what's on your screen

Click **New Topic** to start a fresh Claude conversation for a new subject.

## Tech

Built with Chrome Extensions Manifest V3, vanilla JavaScript, and the Chrome Extensions API.

## Status

Work in progress — actively being built.