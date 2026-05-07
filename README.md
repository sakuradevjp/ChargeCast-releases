# ChargeCast Releases

📦 Public installer downloads for [ChargeCast](https://sakuradevjp.github.io/ChargeCast-notes/) — stream Android games to your PC over USB without a capture card.

## Download

Latest installer: see [Releases](https://github.com/sakuradevjp/ChargeCast-releases/releases/latest).

Also available on the [Microsoft Store](https://apps.microsoft.com/detail/9N87X47V634V).

## SmartScreen warning

This installer is currently unsigned, so Windows SmartScreen will warn the first
time you run it. To install:

1. Click **More info** on the warning dialog
2. Click **Run anyway**

The installer is built from source by sakuradev. To verify the file you
downloaded matches the official release, compare its SHA256 hash against the
value listed on the corresponding Release page.

```powershell
Get-FileHash -Algorithm SHA256 .\ChargeCast-1.7.0-Setup.exe
```

## Reporting issues

[Open an issue](https://github.com/sakuradevjp/ChargeCast-releases/issues) for
bug reports, install problems, or feature requests.

The source repository is private, but issues filed here are read and
responded to.
