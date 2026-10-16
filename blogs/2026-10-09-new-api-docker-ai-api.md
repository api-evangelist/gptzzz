---
title: "New API Docker 部署教程：自建 AI API 中转站"
url: "https://gptzzz.ai/blog/new-api-docker-deploy/"
date: "2026-10-09"
feed_url: "https://gptzzz.ai/blog/feed.xml"
---
New API 用 Docker Compose 部署：克隆官方仓库，改掉 compose 示例密码并设置 SESSION_SECRET，执行 docker compose up -d，再用 Caddy 或 Nginx 配 HTTPS。附初始化、渠道、令牌、curl 验证、升级备份与排错。
