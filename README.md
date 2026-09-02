# King of the Koin - Public Playtest Downloads

This download-only repository hosts official Windows playtest builds of **King of the Koin**. The game source remains private.

## Latest: v0.29.1 - Diverse Klimber Profiles Publication Fix

Download the Windows ZIP from the [v0.29.1 release page](https://github.com/krislovescalifornia/KoinKlimb-Playtest/releases/tag/v0.29.1), extract the entire folder, and run `King of the Koin.exe`.

All players in a match must use the exact same displayed version: **0.29.1**.

## Windows security notice

This invited-friends playtest build is currently **unsigned**, so Windows SmartScreen may show an unrecognized-app warning. Download only from this repository and verify the ZIP before running it.

Expected SHA-256 for `King-of-the-Koin-v0.29.1-windows-x86_64.zip`:

```text
CF40885BCDF151FB663AB89BD02FF20C5ABFBCC525567612A50A2B1B5094B7A2
```

PowerShell verification:

```powershell
(Get-FileHash .\King-of-the-Koin-v0.29.1-windows-x86_64.zip -Algorithm SHA256).Hash
```

If the hash matches, extract the ZIP. If SmartScreen appears, choose **More info**, confirm the app name is `King of the Koin.exe`, then choose **Run anyway**.

## Multiplayer

The ZIP includes `WINDOWS_PLAYTEST.txt` with hosting and joining instructions. Each release also includes a printable friends multiplayer quick-start guide.

This is a pre-1.0 friends playtest. Please share the release-page link rather than re-uploading the executable so everyone receives the same build and checksum.
