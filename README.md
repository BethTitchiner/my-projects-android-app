# My Projects

A simple vibe-coded Android workload organiser with projects, flowchart steps, nested checklists and today's priorities.

## Download and install

Open [the latest release](../../releases/latest) and download **My-Projects.apk** from Assets. Requires Android 8.0 or newer. Open the APK on your phone and, if prompted, allow installation from the app opening the file. For an update, install over your existing app; do not uninstall it first. Export a backup before updating.

This repository contains public downloads and documentation. The source is maintained separately in a private repository. The APK does not contain the private signing key.

## Features

- Projects and linked flowchart steps with nested checklists.
- Persistent today's priorities, including standalone tasks and subtasks; no midnight expiry.
- Drag-and-drop ordering for projects, flowchart steps, tasks and priorities.
- Progress bars, project colours, automatic local saving and undo.
- Manual JSON backup and restore, plus encryption-required Android system cloud backup on supported devices.

## Backups and privacy

Data is stored locally on each user's phone. There is no shared project synchronisation, app account, advertising or analytics, and the app requests no internet permission.

On Android 9 or later, Android can back up app data to the phone's configured backup account when the required end-to-end encryption is available. Enable device backup and set a secure screen lock. Use the app's **Backup settings** menu for guidance. Android controls the schedule; the app cannot confirm a completed upload. Only the latest automatic snapshot is kept. Android 8/8.1 uses manual export only.

Manual JSON exports are unencrypted: store them privately. Backup and restore on real devices should be verified before relying on automatic recovery.

## Updates and support

Updates are downloaded manually from Releases. Each release is signed with the same original signing identity. Release assets include SHA256SUMS.txt for checking the downloaded file.

Report reproducible problems through this repository's Issues. Do not post personal projects, backup files or signing credentials. This is a small independently maintained app; no service availability or support response time is guaranteed.

## Validation

Version 8.0 passes 143 automated model/data checks, Android signature verification and APK alignment checks. Automated on-device gesture and cloud backup/restore testing has not been performed.

See [CHANGELOG.md](CHANGELOG.md) and [LICENSE](LICENSE).
