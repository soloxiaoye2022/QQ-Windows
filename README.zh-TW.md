# QQ for Windows 歷史版本鏡像

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

歸檔騰訊 QQ Windows 客戶端的歷史與最新安裝包。

所有檔案均取自騰訊官方下載源或社群歸檔倉庫，未做任何修改。

## 下載

- 最新版本：[最新 Release](https://github.com/soloxiaoye2022/QQ-Windows/releases/latest)
- 歷史版本：[全部 Releases](https://github.com/soloxiaoye2022/QQ-Windows/releases)

## 架構

| 架構 | 說明 |
| --- | --- |
| x64 | 主流 64 位元 Windows |
| x86 | 32 位元 Windows |
| arm64 | Windows on ARM |

經典版（非 NT 架構）另附 `QQ-9.7.25-classic.exe`。

## 檔案命名

```
QQ-<版本號>-<架構>.exe
```

範例：`QQ-9.9.37-54276-x64.exe`

## 校驗

每個 Release 附帶 `SHA256SUMS`：

```powershell
Get-FileHash .\QQ-9.9.37-54276-x64.exe -Algorithm SHA256
```

## 版本來源

| 來源 | 涵蓋範圍 |
| --- | --- |
| [A-Randomm-User/EXE-save](https://github.com/A-Randomm-User/EXE-save) | 9.9.25 至 9.9.37 全部架構 |
| [Rodert/qq-versions](https://github.com/Rodert/qq-versions) | 部分版本交叉核對 |
| 騰訊官方 CDN | 經典版 9.7.25 |

註：騰訊 `QQNTV2` 路徑對境外 IP 回傳 403，因此新版本主要依賴社群歸檔的實體檔案。

## 說明

本倉庫僅做鏡像分發，不提供任何修改或破解版本。QQ 客戶端版權歸騰訊所有。
