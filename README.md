# Candex

Candex 让你在本地终端里使用 Claude。在项目目录运行 `candex`，用 Claude Code 写代码。

站点：https://candex.dev/

## candex init 怎么配对

注册并登录后，在秘钥页复制 `candex init`，在终端运行一次。打印配对成功后，进入项目目录运行 `candex`。

https://candex.dev/docs/candex-init

## Claude 断线 60 秒怎么接回

连接断开后，Candex 再等 60 秒。这 60 秒内重新连上，刚才的对话还在。超过 60 秒再运行 `candex`，使用 `/resume`。

https://candex.dev/docs/claude-reconnect

## Candex 邀请返现

登录后在概览复制邀请链接。朋友用这条链接注册，并完成第一次充值后，金额的 10% 加到你的余额。只返这一次。

https://candex.dev/docs/candex-invite

## 安装

Mac / Linux：

```bash
curl -fsSL https://candex.dev/api/install.sh | bash
```

Windows PowerShell：

```powershell
irm https://candex.dev/install.ps1 | iex
```

Windows cmd：

```bat
curl -fsSL https://candex.dev/install.cmd -o install.cmd && install.cmd && del install.cmd
```
