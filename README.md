# King of the Koin - Public Playtest Downloads

This download-only repository hosts official Windows playtest builds of **King of the Koin**. The game source remains private.

## Latest: v0.29.4 - Steam Invite Handoff

Download the Windows ZIP from the [v0.29.4 release page](https://github.com/krislovescalifornia/KoinKlimb-Playtest/releases/tag/v0.29.4), extract the entire folder, and run `King of the Koin.exe`.

All players in a match must use the exact same displayed version: **0.29.4**.

## Windows security notice

This invited-friends playtest build is currently **unsigned**, so Windows SmartScreen may show an unrecognized-app warning. Download only from this repository and verify the ZIP before running it.

Expected SHA-256 for `King-of-the-Koin-v0.29.4-windows-x86_64.zip`:

```text
0BF7D377A11C6E984CFF8705840D042C6A4B93B24977BAD6D3FE075B4CD130C7
```

PowerShell verification:

```powershell
(Get-FileHash .\King-of-the-Koin-v0.29.4-windows-x86_64.zip -Algorithm SHA256).Hash
```

If the hash matches, extract the ZIP. If SmartScreen appears, choose **More info**, confirm the app name is `King of the Koin.exe`, then choose **Run anyway**.

## Multiplayer

The ZIP includes `WINDOWS_PLAYTEST.txt` with hosting and joining instructions. Each release also includes a printable friends multiplayer quick-start guide.

This is a pre-1.0 friends playtest. Please share the release-page link rather than re-uploading the executable so everyone receives the same build and checksum.
