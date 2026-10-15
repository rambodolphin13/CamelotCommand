# Camelot Command


A Windows x64 DAoC multibox management application by Aweso, currently available as a tester build.


## Download


Download [CamelotCommand-0.37.1-test.zip](https://github.com/rambodolphin13/CamelotCommand/releases/download/v0.37.1-test/CamelotCommand-0.37.1-test.zip). Extract it and run **CamelotCommand.exe**. Read the [release notes](https://github.com/rambodolphin13/CamelotCommand/releases/tag/v0.37.1-test) for changes and testing guidance. GitHub’s automatically generated source archives do not contain the application.


## First-time setup


The setup walkthrough asks for your DAoC client folder, game settings folder, and an optional Mojo XML import. Scripts are imported separately in the Scripts tab and assigned to teams. Start by testing one client before launching a full team. Close older CC versions before opening this build.


## Included features


- Saved account, character and team launching.
- Window layouts, switching and live previews.
- Background hotkeys, script imports and customizable panels.
- Named chat-log requests, alerts and combat summaries.
- Known-good game settings snapshots, restore with undo, and user.dat protection.
- Session unload, script recipient preview, RenameWin improvements and stuck-input cleanup.
- Local error logging, a dedicated Bug reports tab and manual ZIP export.
- Default client-folder inheritance and account-grouped team creation with one toon per account.
- Optional per-account settings isolation, backup/recovery and refresh after patches.
- Text Pass-through starting at the active client without a driver name or /assist.


Restoring settings requires game clients closed and a relaunch. Login/disconnect confirmation remains manual. Full Mojo script compatibility, remote PCs, health reading and some legacy patches remain incomplete.


## Tester information


This is an unsigned prerelease with the .NET runtime bundled. The 0.37.1 standard build passed 545 automated checks and focused diagnostics checks; live DAoC compatibility still needs feedback. Guides are included in the ZIP. The package excludes personal accounts, passwords, settings snapshots and chat logs. Existing local CC data will still load on an already-configured Windows account.


To report an issue, open the **Bug reports** tab, or **CC crest > Bug report**. Add reproduction steps and the approximate time, review the ZIP, then send it to Aweso through Discord. Nothing is sent automatically. Reports exclude raw exception messages, credentials, account libraries, scripts, chat logs and memory dumps; do not include private information in your typed notes. Native/game crashes may require Windows Reliability Monitor details.


DAoC’s legacy direct login uses process arguments that local inspection tools can read.


## License


Original Camelot Command code is MIT licensed under **Aweso**. The downloadable package includes a consolidated LICENSE.txt with the MIT warranty/liability disclaimer and required third-party notices. This repository hosts tester distribution information; the complete source tree is not yet published.

