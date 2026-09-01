# LinkFlow

LinkFlow 官方 iOS 安装包与版本发布页。

## 下载

请从本仓库的 [Releases](https://github.com/zhosix/linkflow/releases) 下载最新版本，并核对发布页提供的 SHA-256。

当前版本：**2.0.1（构建 20260901）**  
系统要求：**iOS 17 或更高版本**

LinkFlow 提供未签名 IPA，需要使用自己合法持有的证书、描述文件或受信任的安装方式完成签名与安装。请勿从非官方来源下载安装包，也不要向他人提供证书、密码、令牌或配对资料。

## 校验下载文件

macOS：

```bash
shasum -a 256 LinkFlow_2.0.1.ipa
```

Windows PowerShell：

```powershell
Get-FileHash .\LinkFlow_2.0.1.ipa -Algorithm SHA256
```

校验值应与 Release 中的 `SHA256SUMS` 完全一致。

## 支持

- [官方网站](https://linkflow.zhosix.com/)
- [隐私政策](https://linkflow.zhosix.com/privacy)
- 支持与安全问题：`linkflow@zhosix.com`
