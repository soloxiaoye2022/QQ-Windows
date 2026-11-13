# QQ for Windows 历史版本镜像

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

归档腾讯 QQ Windows 客户端的历史与最新安装包。

所有文件均取自腾讯官方下载源或社区归档仓库，未做任何修改。

## 下载

- 最新版本：[最新 Release](https://github.com/soloxiaoye2022/QQ-Windows/releases/latest)
- 历史版本：[全部 Releases](https://github.com/soloxiaoye2022/QQ-Windows/releases)

## 架构

| 架构 | 说明 |
| --- | --- |
| x64 | 主流 64 位 Windows |
| x86 | 32 位 Windows |
| arm64 | Windows on ARM |

经典版（非 NT 架构）另附 `QQ-9.7.25-classic.exe`。

## 文件命名

```
QQ-<版本号>-<架构>.exe
```

示例：`QQ-9.9.37-54276-x64.exe`

## 校验

每个 Release 附带 `SHA256SUMS`：

```powershell
Get-FileHash .\QQ-9.9.37-54276-x64.exe -Algorithm SHA256
```

## 版本来源

| 来源 | 覆盖范围 |
| --- | --- |
| [A-Randomm-User/EXE-save](https://github.com/A-Randomm-User/EXE-save) | 9.9.25 至 9.9.37 全部架构 |
| [Rodert/qq-versions](https://github.com/Rodert/qq-versions) | 部分版本交叉核对 |
| 腾讯官方 CDN | 经典版 9.7.25 |

注：腾讯 `QQNTV2` 路径对境外 IP 返回 403，因此新版本主要依赖社区归档的实体文件。

## 说明

本仓库仅做镜像分发，不提供任何修改或破解版本。QQ 客户端版权归腾讯所有。
