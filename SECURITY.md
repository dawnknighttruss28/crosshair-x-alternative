# Security Policy

## Supported versions

| Version | Supported |
|---|---|
| 1.0.x | Yes |
| Older builds | No, download the current one from the landing page |

## What this tool does and does not do

Crosshair X Alternative is an external overlay. It draws a transparent, always-on-top window above your desktop and writes its own settings file next to the application.

It does not:

- open, read, modify or patch any game installation;
- attach to, inject into or hook any running process;
- install a driver, a kernel component or a Windows service;
- request administrator rights;
- capture your screen, keystrokes or game window.

There is no telemetry, no account system and no background updater. Uninstalling means deleting the folder.

## Reporting a vulnerability

If you believe you have found a security issue, open a private report through GitHub's **Security → Report a vulnerability** flow on this repository rather than a public issue.

Please include:

- the version shown in the app and on the landing page;
- your Windows build;
- the exact steps that reproduce the problem;
- what you expected to happen and what happened instead.

You can expect an acknowledgement within a few days. Please give a reasonable window for a fix before publishing details.

## Scope

Reports about a game, its publisher, store listings or tournament rules are out of scope for this repository. This policy covers the overlay application and this project page only.

## Distribution

Builds are distributed through the project landing page only. If you obtained this tool from anywhere else, treat that copy as untrusted.
