# UZIT Hub installers

The installer for **UZIT Hub**, the launcher for UZIT Kitchens & Robes' tools. For UZIT staff PCs.

## Install

1. Open the latest release: https://github.com/MattOC-dev/uzit-hub-releases/releases/latest
2. Under **Assets**, download `UZIT-Hub-Setup-<version>.exe` and run it. It installs for your user only; no admin rights needed.
3. The first time, Windows says "Windows protected your PC" because the installer isn't code-signed yet. Click **More info**, then **Run anyway**.

## Updates

Nothing to do. The Hub checks here itself, lights a dot when a newer version is ready, and installs it when you click **Install now**.

## About this repository

It holds only installers and `latest.json`, which the Hub reads. The source code is in a private repository; GitHub builds, tests and publishes every release from it. Nothing here is uploaded by hand.