# Graphite to GitHub PR Redirector

A Chrome extension that automatically redirects Graphite PR links to their corresponding GitHub PR pages.

## What it does

Converts URLs like:
- `https://app.graphite.dev/github/pr/facebook/react/102/`

To:
- `https://github.com/facebook/react/pull/102`

## Installation

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" in the top right corner
3. Click "Load unpacked"
4. Select the `graphite-redirect` folder
5. The extension will now automatically redirect Graphite PR links to GitHub

## How it works

The extension uses Chrome's Declarative Net Request API to intercept and redirect Graphite PR URLs before they load, providing instant redirection to the corresponding GitHub PR page.

## Files

- `manifest.json` - Extension configuration
- `rules.json` - Redirect rules using regex pattern matching
- `icon*.png` - Extension icons in various sizes
