<h1>
  <img src="https://d3bywedspcdj3v.cloudfront.net/logo.png" alt="RAOfflineProxy logo" width="40">
  RAOfflineProxy Nightly
</h1>

Automated development builds of [RAOfflineProxy](https://github.com/misantronic/RAOfflineProxy).

> [!WARNING]
> Nightly builds are **untested** snapshots of the latest code. They can contain bugs, break features or lose cached data.
> **If you just want to use RAOfflineProxy, download the stable version from the [main releases page](https://github.com/misantronic/RAOfflineProxy/releases) instead.**

## Downloads

| Platform | Release |
|---|---|
| Android | [`nightly-android`](https://github.com/misantronic/RAOfflineProxy-nightly/releases/tag/nightly-android) |
| Linux | [`nightly-linux`](https://github.com/misantronic/RAOfflineProxy-nightly/releases/tag/nightly-linux) |

Each release is replaced automatically whenever the Android or Linux code changes. The release notes link the exact commit it was built from.

Installation works exactly like the stable version, see the [documentation](https://raofflineproxy.com).

## Versions and updates

Nightly versions look like `1.13.0-alpha1-nightly.42`: the version they are based on, plus a build number.

- A nightly install's update check offers newer nightlies, and a stable release once one is newer than the nightly's base version.
- Stable installs never see nightlies.
- The Android nightly is signed like the stable app, so it installs over it and keeps your data. The next stable release installs over a nightly the same way.

To go back to stable, install the latest stable release over the nightly.

## Reporting bugs

Include the full nightly version (shown in the app) in your report. Use the [issue tracker](https://github.com/misantronic/RAOfflineProxy/issues), the [Contact / Feedback Form](https://forms.gle/XPRfWe2hAqzYy3JX9) or [Discord](https://discord.gg/aSuFFUsgqb).

This repository only hosts builds; the source code lives in [misantronic/RAOfflineProxy](https://github.com/misantronic/RAOfflineProxy).
