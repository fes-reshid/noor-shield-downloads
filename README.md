# Noor Shield downloads

Windows and Mac installers for **Noor Shield**. This repository holds release
files only — there is no source code here.

**Download the latest version:** see [Releases](../../releases/latest), or visit
[noorshield.com](https://noorshield.com). The Mac version is a test version for
now, under [Releases](../../releases) as "Noor Shield for Mac".

Each installer comes with a `.sha256.txt` file. To check your download wasn't
corrupted or altered, run this in PowerShell and compare the result with that file:

```powershell
Get-FileHash "Noor-Shield-Setup-<version>.exe" -Algorithm SHA256
```

On a Mac, in Terminal:

```sh
shasum -a 256 Noor-Shield-<version>-Mac.pkg
```
