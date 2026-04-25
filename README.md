# RainClaw

## 网站描述
RainClaw 是一个智能任务助手，让复杂任务变得简单。基于先进的 LLM 技术，支持多种模型，提供丰富的技能和工具扩展系统。

主要功能包括：
- 多用户隔离与安全保障
- 自定义垂直领域工作
- 直观的会话界面
- 丰富的技能生态
- 灵活的模型选择
- 智能记忆系统
- 网站开发：用户无需编程基础，仅需通过自然语言描述需求，该工具最快1分钟即可自动生成包含前端、后端代码的完整网站或H5页面，并支持在阿里云上一键部署上线

## 阿里云部署信息

### 部署目录
- 网站部署目录：`/usr/share/nginx/html`

### 配置文件
- 入口配置：`/etc/nginx/nginx.conf`
- 网站配置：`/etc/nginx/conf.d/laogu.me.conf`

### 证书管理
- 自动续期证书：`sudo certbot renew --dry-run`

### Nginx 命令
- 启动/重载 Nginx：`sudo systemctl reload nginx`
- 检查 Nginx 配置：`nginx -t`