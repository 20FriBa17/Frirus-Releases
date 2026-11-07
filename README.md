# Frirus Releases

This repository contains **public, signed-off release packages only** for Frirus.

- The application source code remains in the private `20FriBa17/Frirus` repository.
- Downloadable builds are published as GitHub Release assets.
- The updater consumes the `latest.json` asset from the latest release.
- Development builds and CI artifacts are not published here.

## Installing

Download `Frirus-win-x64.zip` from the latest release, extract it to a folder you can write to (for example, `%LOCALAPPDATA%\\Programs\\Frirus`), and run `Frirus.exe`.

Updates will only be offered by the application after a release has been published and its package hash can be verified.

## Release metadata

Each release includes `latest.json` with the version, package URL, and SHA-256 digest. The updater must verify the digest before installing any package.
