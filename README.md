# Aven Local downloads

This repository contains binary releases, download instructions and checksums only. Application and companion source and build workflows are private.

## Windows x64

[Download Aven Local for Windows](https://github.com/camcreations/aven-local-downloads/releases/latest/download/Aven-Local-Windows-x64.zip)

1. Download and Extract All.
2. Open the Aven Local folder and double-click Aven Local.exe. Keep the _internal folder beside it.
3. Choose an existing project folder, enter the build ID from Playground, and approve the device/build/directory in the browser.
4. Keep the helper window open while syncing. Use Ctrl+C or https://aven.quest/pair to disconnect and revoke access.

Python and Tcl/Tk are bundled. No separate Python install, terminal command, Git checkout, administrator access or copied browser cookie is needed. The app is unsigned; Windows or antivirus may warn or block it. Do not disable security protections. SHA256SUMS.txt checks integrity, not publisher identity.

This helper provides file access only. Project execution, dependency installation and publishing are separate approvals. Local edits are preserved as conflicts; prior versions are retained as .aven-backup-* siblings.

## Linux

A packaged Linux download is not available yet. Do not run the Windows executable on Linux.

GitHub automatically labels release documentation archives as 'Source code'. Those archives contain this download repository's instructions only, not Aven source code.
