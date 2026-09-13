# A desktop project dashboard for work you do with AI

First Officer helps you see where your projects stand, what needs your decision
and what to do next. Keep using your own AI app that can work with local files.

[Choose the Mac or Windows download](https://www.keithstaggers.com/first-officer/).
Then follow [Getting started](GETTING-STARTED.md).

Less managing AI. More finished work. You're still in charge.

## Free early release

Version 0.1.0-dev.19 is free to use. The development source is kept private.
Your own AI service may charge separately. First Officer does not include an AI,
sign you into one, or send instructions on your behalf.

This repository holds public download information and third-party notices,
not the First Officer development tree. The app downloads are attached to
the versioned release. GitHub's automatic source archives contain only this
public repository's documents.

## Mac ZIP correction: repack.1

The original dev.19 Mac ZIP could leave extra metadata files inside the app,
causing macOS to reject its signature. Use the [corrected Mac ZIP](https://github.com/Kcstaggers/first-officer-releases/releases/download/v0.1.0-dev.19/First-Officer-0.1.0-dev.19-mac-arm64-repack.1.zip)
instead of the original Mac ZIP. The app version and signed program files are
unchanged; this corrects the ZIP packaging only. The Windows installer is unchanged.

The corrected package passes strict signature, notarization-ticket and Apple
distribution checks after independent extraction and Finder extraction. A fresh
internet-download and normal-opening check is still pending. If a security warning
appears, stop and report its exact text. Do not disable protections or use an override.

## Before you start

- Mac: Apple silicon, macOS 13 or later.
- Windows: 64-bit Intel or AMD processor, Windows 10 or later.
- These are runtime minimums, not testing of every operating-system version.
- Intel Mac and Windows ARM packages are not included.
- Start with a non-sensitive project and keep backups.

First Officer displays saved records. It cannot guarantee that an outside AI
follows the instructions, records every action, or leaves every file alone.
An AI's report is not independent proof that work is finished.

Read [Release notes and known limits](RELEASE-NOTES.md).
[SHA256SUMS.txt](SHA256SUMS.txt) identifies current and earlier download files.
[Third-party notices](THIRD-PARTY-NOTICES.md) links the notices included in them.

## Feedback

Email kcstaggers@gmail.com with the app version, your computer type, what you
tried and what happened. Do not send private project contents, passwords or keys.
