# DeskOS support

DeskOS is a desktop-style workspace for iPhone and iPad, with built-in tools, file browsing, website shortcuts, and phone input controls.

This repository contains the public support and privacy pages and the issue tracker. It does not contain the DeskOS app source code.

- [DeskOS on the App Store](https://apps.apple.com/app/id6811301816)
- [Support page source](index.html)
- [Privacy page source](privacy.html)
- [Search existing issues](https://github.com/mz1-mzone/deskos-support/issues)
- [Report a bug](https://github.com/mz1-mzone/deskos-support/issues/new?template=bug_report.yml)

## Getting started with a display

1. Connect your device and display using your intended cable, adapter, hub, or wireless connection.
2. Open DeskOS and keep it active while checking the display.
3. Check what appears on **both** screens. Record whether the monitor shows a separate workspace, a copy of the phone screen, a blank screen, or another result.

DeskOS includes a separate external-display mode and on-device preview/input layouts. The connection method, display hardware, iOS behavior, and app version matter. Seeing a mirrored image alone does not establish that a separate DeskOS workspace is active. Do not assume that every USB-C, HDMI, hub, or AirPlay setup behaves identically.

If the display only mirrors the phone, describe exactly where any “Desktop Preview” label appears and which controls remain available on the phone. Include screenshots of both screens if possible. These details help investigate the behavior; they do not identify its cause on their own.

## Reporting a problem

Search existing issues first. If one describes the same problem, add your setup and reproduction details there instead of opening a duplicate.

Use the bug-report form and include:

- Device model and exact iOS or iPadOS version.
- DeskOS version, build number if available, and whether it came from the App Store or TestFlight. Please avoid “latest” or “newest.”
- Steps to reproduce, expected behavior, and actual behavior.
- For display problems: wired or wireless connection, exact display/receiver and adapter/hub/cable models if known, and what each screen shows.
- For input problems: mouse/keyboard models, connection method, relevant accessibility settings, and the affected app/tool.
- Screenshots or a short recording, with personal information removed.

Issues and attachments are **public**. Do not post passwords, API keys, verification or promo codes, account details, private files, or unredacted messages. Do not upload complete logs without checking them for sensitive information.

## Scope and limitations

DeskOS uses its own tools and website shortcuts; it does not run arbitrary installed iPhone apps inside its windows. Website sign-in, media playback, uploads, and editing behavior depend on the provider. Mouse behavior depends on the input events delivered by iOS.

A report or reproduction request is not confirmation of a defect, a promised feature, or a release date.
