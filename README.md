# MQM AI Evaluator — Releases / 安装包发布

本仓库**只存放安装包与自动更新元数据**（`latest.yml`、`*.blockmap`），不包含源代码。
源代码仓库：[MQM-AI-Evaluator](https://github.com/Ceativeman/MQM-AI-Evaluator)

This repository hosts **installer artifacts and auto-update metadata only**.
Source code: https://github.com/Ceativeman/MQM-AI-Evaluator

## 下载 / Download

前往 [Releases](https://github.com/Ceativeman/MQM-AI-Evaluator-Release/releases/latest) 下载最新版 `MQM-AI-Evaluator-Setup-x.y.z.exe`。

国内镜像下载：在 GitHub 链接前加镜像前缀，任选其一，例如

```
https://ghfast.top/https://github.com/Ceativeman/MQM-AI-Evaluator-Release/releases/latest/download/latest.yml
https://gh-proxy.com/https://github.com/Ceativeman/MQM-AI-Evaluator-Release/releases/latest/download/latest.yml
```

## 自动更新 / Auto-update

应用内「检查更新」读取本仓库 `releases/latest/download/latest.yml` 检测新版本，
并支持多个国内镜像测速与回退。发布新版本时，源仓库的 GitHub Actions
（推送 `v*` 标签触发）会自动构建安装包并发布到本仓库。
