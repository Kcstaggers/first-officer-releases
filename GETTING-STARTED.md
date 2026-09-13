# Start a project with First Officer

## Mac ZIP correction: repack.1

The original dev.19 Mac ZIP could leave extra metadata files inside the app,
causing macOS to reject its signature. Use the [corrected Mac ZIP](https://github.com/Kcstaggers/first-officer-releases/releases/download/v0.1.0-dev.19/First-Officer-0.1.0-dev.19-mac-arm64-repack.1.zip)
instead of the original Mac ZIP. The app version and signed program files are
unchanged; this corrects the ZIP packaging only. The Windows installer is unchanged.

The corrected package passes strict signature, notarization-ticket and Apple
distribution checks after independent extraction and Finder extraction. A fresh
internet-download and normal-opening check is still pending. If a security warning
appears, stop and report its exact text. Do not disable protections or use an override.

## Before installing on Windows

This early Windows installer showed a SmartScreen "unrecognized app" warning
in our test. It is signed by Keith Staggers, but signing does not guarantee
safety or a warning-free installation. New signed apps can still lack download
reputation. [Microsoft explains this warning](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

Download only from the official First Officer page. If a warning appears,
stop and check its exact message and publisher. Do not disable Windows
protections. If you are unsure, choose Don't run and contact us using the
feedback address below.

## Your first project

1. Install the package for your computer. On Mac, open the ZIP, move First Officer
   to Applications and open it there. On Windows, open the installer and follow
   the steps for your current Windows account. Do not disable security protections.
2. Choose Set up my workspace and create a new folder. If an earlier workspace
   opens, choose Folder at the top, then Create another workspace.
   On Windows, choose where the new folder should go and give it a new name.
   Choosing an existing folder can move the window into it without creating
   anything. Cancel if you are unsure; do not delete existing work to make room.
3. Copy the workspace location and the first-project instruction. Add that folder
   in an AI app that can read and write local files, then paste the instruction.
   Pasting a path into an ordinary web chat does not grant file access.
4. Try a small non-sensitive project. For example: Read START-HERE.md. Help me
   plan a three-day trip and keep this project's records up to date.
5. Return to First Officer and choose Check for updates to refresh saved records.
6. When a decision needs you, write a reply, review the instruction and choose
   Copy for my AI. Paste it into your AI yourself.

The AI needs to keep the records up to date. A file change or reported result
is not independent proof that a task is finished.

Keep your workspace and app settings backed up. Keep the workspace folder when
updating or uninstalling the app. Updates are manual. Do not delete older
project work or reset a profile merely because the app opens an earlier folder.

Feedback: kcstaggers@gmail.com. Say which computer and app version you used,
what you tried and what happened. Leave out private project contents, passwords
and account credentials.
