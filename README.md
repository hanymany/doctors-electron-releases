# Doctors Desktop: releases

This repository holds **release files only** for the Doctors Desktop Windows application (an Electron shell for
`https://mahalla-doctors.com/`). It contains no source code, secrets or patient data.

- Installed apps check this repository's **published** GitHub Releases for updates (electron-updater, `latest.yml`).
  **Draft** releases are invisible to installed apps.
- Releases are created as drafts by a manual, reviewed CI job in the private source repository. The owner
  publishes each one by hand.
- Current builds are **unsigned internal-test builds**: Windows shows "Unknown publisher". Do not distribute
  them as trusted software.

Please do not open issues here; this repository is not monitored for support.
