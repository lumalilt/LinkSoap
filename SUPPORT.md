# Support

## Where to ask for help

- Bug reports: [open a GitHub issue](https://github.com/lumalilt/NWSHelper/issues/new/choose) with the bug report template.
- Feature requests: [open a GitHub issue](https://github.com/lumalilt/NWSHelper/issues/new/choose) with the feature request template.
- Security issues: follow [SECURITY.md](SECURITY.md) instead of opening a public issue.

## Before filing an issue

- Confirm the problem on the latest public release if possible.
- Note which install channel you are using:
  - direct installer
  - portable zip
  - Microsoft Store
- Capture the app version and operating system details.
- For updater issues, note whether the problem involves appcast download, signature verification, or installer launch.

## What to include

- app version
- install channel
- Windows version
- exact steps to reproduce
- expected result
- actual result
- screenshots or logs when safe to share

Do not include license keys, client secrets, signing certificates, or other credentials.

## Release troubleshooting

- Direct-download releases are expected to include installer, portable archives, update metadata, checksums, and stable appcast artifacts.
- MSIX is not guaranteed on every GitHub Release; it is published only when the direct-download MSIX lane is explicitly enabled or when Store packaging is part of the release operation.
- Store installations and direct-download installations are separate servicing channels. Store updates should come from the Store, not GitHub installer downloads.

## Maintainer triage expectations

- Public-source build, packaging, updater, and docs issues belong in this repo.
- Private-source Core implementation issues may be fixed from the private repo and then consumed here through a released package update.
