---
title: Hermes Agent 使用备忘
date: 2026-06-21
tags: [Hermes, AI, 配置]
---

## 环境信息

- 本机路径: /opt/data/home/
- 预编译程序: /opt/data/prebin/（已有 curl、vim）
- 飞书 App ID: cli_a967072346e19bdb
- lark-cli: /opt/data/home/lark-cli-package/package/bin/lark-cli
- Python: 3.13
- OS: Debian（Docker 容器）

## 注意事项

- 没有 ssh 客户端，下载静态编译的放到 prebin 即可
- 没有 curl（但 prebin 里有一个）
- apt 没有 sudo 权限
- 文件权限问题：修改 /opt/data/ 下的文件后要 chown hermes:hermes
