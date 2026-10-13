# XBrain releases

XBrain is a second brain of your own: notes, tasks, rules, skills, a terminal and an MCP server for
agents, working locally on your Mac. This repository holds its releases only; the source is private.

## Install

1. Open [Releases](https://github.com/vlad-demchyk/xbrain-releases/releases/latest) and download
   `XBrain_<version>_aarch64.dmg`.
2. Open the DMG and drag XBrain into Applications.
3. The application is not notarised by Apple. On the first start macOS refuses it: open
   System Settings → Privacy & Security and choose "Open Anyway" next to XBrain.

XBrain checks for a new version on start and once a day, and updates itself from the window
(Settings → Updates). The update replaces the application and its background service together.

## What is here

- `XBrain_<version>_aarch64.dmg`: the installer.
- `XBrain.app.tar.gz` and `XBrain.app.tar.gz.sig`: the update the application downloads, and its
  signature; an update with a wrong signature is refused.
- `latest.json`: the newest version, read by the application when it checks for updates.

## Terms of use

XBrain is free to use for personal and commercial work. It is provided as is, without warranty of
any kind. Redistributing or modifying the application is not permitted without the author's
permission. Your notes stay on your machine; XBrain sends nothing anywhere unless you turn sync on.
