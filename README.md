# hello-workbuddy

WorkBuddy 与 GitHub 链接的测试仓库，用于验证本机到 GitHub 的完整链路是否畅通。

## 验证目标

- [x] 账号认证（Git Credential Manager + HTTPS）
- [x] 本地提交
- [x] 推送到远程
- [x] 远程可见

## 环境说明

本仓库建立于 2026-11-04，用于排查并验证以下问题：

| 问题 | 原因 | 处理 |
| --- | --- | --- |
| 浏览器打不开 github.com | hosts 被 Steam++ 残留写成 `127.0.0.1` | 清理 hosts |
| SSH 密钥无法加载 | Windows 中文用户名导致路径 GBK 编码错乱 | 改用 HTTPS + GCM |
| git 账号与 GitHub 不匹配 | 本地配置为 `meihaodegenhaosan`，实际账号是 `Sjsibdd` | 仓库级单独配置 |

## 结论

本机直连 GitHub 无需代理或加速器。

## 对应 GitHub 账号

https://github.com/Sjsibdd
