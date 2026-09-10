# LinkFlow

[简体中文](#linkflow) | [English](#english)

LinkFlow 官方 iOS 安装包与版本发布页。

## 下载

请从本仓库的 [Releases](https://github.com/zhosix/linkflow/releases) 下载最新版本，并核对发布页提供的 SHA-256。

当前版本：**2.0.5（构建 20260910）**  
系统要求：**iOS 17 或更高版本**

LinkFlow 提供未签名 IPA，需要使用自己合法持有的证书、描述文件或受信任的安装方式完成签名与安装。请勿从非官方来源下载安装包，也不要向他人提供证书、密码、令牌或配对资料。

## 校验下载文件

macOS：

```bash
shasum -a 256 LinkFlow_2.0.5.ipa
```

Windows PowerShell：

```powershell
Get-FileHash .\LinkFlow_2.0.5.ipa -Algorithm SHA256
```

校验值应与 Release 中的 `SHA256SUMS` 完全一致。

## 支持

- [官方网站](https://linkflow.zhosix.com/)
- [隐私政策](https://linkflow.zhosix.com/privacy)

---

## English

Official iOS downloads and releases for LinkFlow.

### Download

Download the latest version from this repository's [Releases](https://github.com/zhosix/linkflow/releases) and verify its SHA-256 checksum against the one provided on the release page.

Current version: **2.0.5 (build 20260910)**  
Requires: **iOS 17 or later**

LinkFlow is distributed as an unsigned IPA. Sign and install it using certificates and provisioning profiles you lawfully hold, or a trusted installation method. Do not download installation packages from unofficial sources or share your certificates, passwords, tokens, or pairing data with others.

### Verify your download

macOS:

```bash
shasum -a 256 LinkFlow_2.0.5.ipa
```

Windows PowerShell:

```powershell
Get-FileHash .\LinkFlow_2.0.5.ipa -Algorithm SHA256
```

The checksum must exactly match the value in the release's `SHA256SUMS` file.

### Support

- [Official website](https://linkflow.zhosix.com/)
- [Privacy policy](https://linkflow.zhosix.com/privacy)
