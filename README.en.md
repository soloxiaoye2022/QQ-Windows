# QQ for Windows Release Archive

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

Archived installers for the Tencent QQ Windows client, past and present.

Every file comes from Tencent's official download sources or community archives, unmodified.

## Download

- Latest: [latest release](https://github.com/soloxiaoye2022/QQ-Windows/releases/latest)
- Historical: [all releases](https://github.com/soloxiaoye2022/QQ-Windows/releases)

## Architectures

| Arch | Notes |
| --- | --- |
| x64 | Mainstream 64-bit Windows |
| x86 | 32-bit Windows |
| arm64 | Windows on ARM |

The classic (non-NT) build ships as `QQ-9.7.25-classic.exe`.

## File naming

```
QQ-<version>-<arch>.exe
```

Example: `QQ-9.9.37-54276-x64.exe`

## Verify

Each release ships a `SHA256SUMS` file:

```powershell
Get-FileHash .\QQ-9.9.37-54276-x64.exe -Algorithm SHA256
```

## Provenance

| Source | Coverage |
| --- | --- |
| [A-Randomm-User/EXE-save](https://github.com/A-Randomm-User/EXE-save) | 9.9.25 through 9.9.37, all architectures |
| [Rodert/qq-versions](https://github.com/Rodert/qq-versions) | Cross-check for selected versions |
| Tencent official CDN | Classic build 9.7.25 |

Note: Tencent's `QQNTV2` path returns 403 for non-China IPs, so newer versions rely on community-archived binaries.

## Notes

This repository only mirrors and distributes packages. It provides no modified or cracked clients. The QQ client is copyright Tencent.
