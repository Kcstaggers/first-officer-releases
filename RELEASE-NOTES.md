## Mac ZIP correction: repack.1

The original dev.19 Mac ZIP could leave extra metadata files inside the app,
causing macOS to reject its signature. Use the [corrected Mac ZIP](https://github.com/Kcstaggers/first-officer-releases/releases/download/v0.1.0-dev.19/First-Officer-0.1.0-dev.19-mac-arm64-repack.1.zip)
instead of the original Mac ZIP. The app version and signed program files are
unchanged; this corrects the ZIP packaging only. The Windows installer is unchanged.

The corrected package passes strict signature, notarization-ticket and Apple
distribution checks after independent extraction and Finder extraction. A fresh
internet-download and normal-opening check is still pending. If a security warning
appears, stop and report its exact text. Do not disable protections or use an override.

# First Officer 0.1.0-dev.19

A desktop project dashboard for work you do with AI.

See saved projects, decisions and next steps while continuing to use your own
folder-capable AI. First Officer creates a workspace with instructions and
project records. Give that folder to your AI using its own file-access controls.

## Packages

- Mac: Apple silicon, macOS 13 or later.
- Windows: x64 Intel or AMD processor, Windows 10 or later.

These are runtime minimums, not proof of testing every operating-system version.
Intel Mac and Windows ARM packages are not included.

## Recorded checks

The final packages were checked on an Apple-silicon Mac running macOS 26.6.2
and a Windows x64 PC running Windows 11 Home, build 26200. The Windows check
used a one-time owner-operated SmartScreen exception. Installation, new workspace
creation, record refresh, copying, saved replies and reopening were observed.
Windows uninstall preserved the checked settings and project files; a small
diagnostic log remained in the app folder.

One Windows folder-picker check was inconclusive: choosing an occupied folder
moved the save window into that folder instead of reaching the app's refusal
message. The existing file was unchanged. The unchanged folder-creation code
passed earlier Windows refusal tests, but that is not a final native-dialog pass.

## What to expect

This is an early release. Keep backups and start with a non-sensitive project.
First Officer displays saved records. It does not automatically capture every
AI action, connect to your AI account, enforce an outside AI's permissions or
guarantee that records are complete. Copying a decision does not send it or
authorize an action by itself.

Updates are manual. Check for updates inside the app refreshes project records,
not the software. Get future app versions from the official download page and
read that version's instructions before installing.

App settings and saved replies can be separate from the workspace. Do not treat
a copied workspace as a complete app backup.

## Windows installation warning

The signed Windows installer showed a SmartScreen "unrecognized app" warning
in our test. The publisher is Keith Staggers. A valid signature does not
guarantee safety or remove warnings for a new app.
[Microsoft explains how app reputation works](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

If a security warning appears, keep protections enabled and note its exact text.
For feedback, email kcstaggers@gmail.com. Include the app version, computer type
and what happened. Do not send private project contents, passwords or keys.

Wider assistant, accessibility and operating-system coverage is still being
evaluated. This release does not claim completion of that broader qualification.

See GETTING-STARTED.md for the first workflow and SHA256SUMS.txt to identify
the exact download files. Required third-party notices ship inside the app.
