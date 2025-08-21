# Worklog Desktop Distribution

This repository contains the distribution assets for [Worklog Desktop](https://worksome.app), a macOS application for tracking and managing work items with markdown support.

## About

Worklog Desktop is distributed directly outside the Mac App Store using [Sparkle](https://sparkle-project.org/) for automatic updates. This repository hosts the distribution files served via GitHub Pages.

## Distribution Files

- `appcast.xml` - Sparkle appcast feed for automatic updates
- `release-notes.md` - Latest release notes and changelog

## Installation

### Download

Download the latest version from the [main repository releases](https://github.com/ayeganyan/Worklog-Desktop/releases).

### First Installation

Since Worklog Desktop uses self-signed certificates, you'll need to bypass macOS Gatekeeper warnings:

1. Download the DMG from GitHub Releases
2. Open the DMG and drag the app to Applications
3. **Right-click** the app in Applications → **"Open"**
4. Click **"Open"** in the security dialog
5. App will launch and auto-updates will work normally thereafter

### Alternative Method

1. Open System Preferences → Security & Privacy
2. After attempting to launch, click "Allow" next to the blocked app warning

## Auto-Updates

Once installed, Worklog Desktop automatically checks for updates daily using the Sparkle framework. Updates are verified using Ed25519 signatures to ensure authenticity.

## Support

For support, issues, or feature requests, please visit the [main repository](https://github.com/ayeganyan/Worklog-Desktop).

## Privacy

This distribution repository only contains public release information. The main source code repository may be private.

---

*Distributed via GitHub Pages • Updated automatically via GitHub Actions*