# King of the Koin - Public Playtest Downloads

This download-only repository hosts official Windows playtest builds of **King of the Koin**. The game source remains private.

## Download v0.12.0 - Koin Zone Showdown

Download the Windows ZIP from the [v0.12.0 release page](https://github.com/krislovescalifornia/KoinKlimb-Playtest/releases/tag/v0.12.0), extract the entire folder, and run `King of the Koin.exe`.

All players in a match must use the exact same displayed version: **0.12.0**.

## Windows security notice

This invited-friends playtest build is currently **unsigned**, so Windows SmartScreen may show an "unrecognized app" warning. Download only from this repository and verify the ZIP before running it.

Expected SHA-256 for `King-of-the-Koin-v0.12.0-windows-x86_64.zip`:

```text
7D9B3F86A9477959BBB52009C93E70C651331AC7566627E0ADDF3220C69DEB59
```

PowerShell verification:

```powershell
(Get-FileHash .\King-of-the-Koin-v0.12.0-windows-x86_64.zip -Algorithm SHA256).Hash
```

If the hash matches, extract the ZIP. If SmartScreen appears, choose **More info**, confirm the app name is `King of the Koin.exe`, then choose **Run anyway**.

## Multiplayer

The ZIP includes `WINDOWS_PLAYTEST.txt` with hosting and joining instructions. The release also includes a printable friends multiplayer quick-start guide.

This is a pre-1.0 friends playtest. Please share the release-page link rather than re-uploading the executable so everyone receives the same build and checksum.