# Notion Assignment Import (Forked)

A Chrome extension to sync `Canvas` assignments to `Notion` automatically.

> Automatically sync all your `Canvas` courses to `Notion`. Works silently in the `background` while protecting your `privacy`. Get `desktop alerts` when a sync completes.

## Quick Start
1. `Install` the extension by loading `dist/chromium` in Chrome.
2. Get a `Notion Token` and duplicate this [database template](https://jamesnzl-sandbox.notion.site/c4d73bebd39c4103b96b2edb8be9e0bd).
3. `Connect` the integration to your Notion database.
4. `Configure` the options with your token and database ID.
5. `Automate` by enabling `background sync` in the settings.

## How it works
> This fork uses `chrome.alarms` to trigger a background worker. It fetches your `Canvas` course list and pushes new or updated assignments to `Notion` automatically.
