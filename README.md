# MQM AI Evaluator — Releases / 安装包发布

本仓库**只存放安装包与自动更新元数据**（`latest.yml`、`*.blockmap`），不包含源代码。

This repository hosts **installer artifacts and auto-update metadata only**.

## 下载 / Download

前往 [Releases](https://github.com/Ceativeman/MQM-AI-Evaluator-Release/releases/latest) 下载最新版 `MQM-AI-Evaluator-Setup-x.y.z.exe`。

国内镜像下载：在 GitHub 链接前加镜像前缀，任选其一，例如

```
https://ghfast.top/https://github.com/Ceativeman/MQM-AI-Evaluator-Release/releases/latest/download/latest.yml
https://gh-proxy.com/https://github.com/Ceativeman/MQM-AI-Evaluator-Release/releases/latest/download/latest.yml
```

## 自动更新 / Auto-update

应用内「检查更新」读取本仓库 `releases/latest/download/latest.yml` 检测新版本，
并支持多个国内镜像测速与回退。新版本由 GitHub Actions 自动构建并发布到本仓库。
