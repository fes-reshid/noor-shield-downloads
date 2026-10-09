# Noor Shield downloads

Windows installers for **Noor Shield**. This repository holds release files
only — there is no source code here.

**Download the latest version:** see [Releases](../../releases/latest), or visit
[noorshield.com](https://noorshield.com).

Each installer comes with a `.sha256.txt` file. To check your download wasn't
corrupted or altered, run this in PowerShell and compare the result with that file:

```powershell
Get-FileHash "Noor-Shield-Setup-<version>.exe" -Algorithm SHA256
```
