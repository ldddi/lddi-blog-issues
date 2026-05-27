# lddi.net — Blog

[中文](#文章) | [English](#posts)

---

## 文章

| 标题 | 简介 | 链接 |
|------|------|------|
| Cloudflare Tunnel 实战：免公网 IP 把内网服务安全暴露到互联网 | 没有公网 IP、不想买 VPS、不愿在路由器上开端口转发？Cloudflare Tunnel 用一条出站隧道就能把家里的 NAS、博客、HomeAssistant 安全发布到互联网。本文从原理讲到一键部署。 | [阅读](https://lddi.net/zh/blog/cloudflare-tunnel-guide) |
| Telegram Bot 开发完全指南：从创建到部署 | 手把手教你创建 Telegram 机器人：从 BotFather 注册、选择开发框架、编写代码到部署上线，覆盖 Python 和 Node.js 两种方案。 | [阅读](https://lddi.net/zh/blog/create-telegram-bot) |
| SSH 密钥认证完全指南：告别密码，安全登录你的 VPS | 从原理到实操，彻底搞懂 SSH 密钥认证。覆盖密钥生成、VPS 免密登录配置、Windows 本地配置，附带常见踩坑解决方案。 | [阅读](https://lddi.net/zh/blog/ssh-key-authentication-guide) |
| HostDare vs 搬瓦工：线路、带宽与价格对比 | 从 CN2 GIA 线路质量、晚高峰稳定性、IP 被墙概率到协议兼容性，实测对比 HostDare 和搬瓦工在科学上网场景下的真实表现。 | [阅读](https://lddi.net/zh/blog/hostdare-vs-bandwagonhost-proxy) |
| 现代域名实战：从注册商选择到 DNS、SPF/DKIM/DMARC 全配置 | 买域名只是开始——选错注册商一年多付几百，DNS 记录配错全站访问异常，邮箱没配 SPF 直接进垃圾箱。本文一次讲透注册商对比、记录类型、邮箱反垃圾铁三角和域名安全。 | [阅读](https://lddi.net/zh/blog/domain-dns-mastery) |
| Cron 表达式从入门到精通：5 个字段背后的逻辑与踩坑 | 看似简单的 5 个字段，写错一个就可能让备份脚本一年只跑一次。本文系统梳理 Cron 表达式的语法、各方言差异、常见误用与实战范例。 | [阅读](https://lddi.net/zh/blog/cron-expression-mastery) |
| Self-Hosted 全家桶：用 Docker Compose 跑出你自己的云 | 把 Google Drive、密码管理、相册、笔记、监控统统搬到自己的服务器。本文用 Docker Compose 串起 10 个值得自托管的应用，配合反代和备份方案，搭一套数据完全归你的私有云。 | [阅读](https://lddi.net/zh/blog/self-hosted-stack) |
| Hash 算法横评：MD5/SHA-1/SHA-256/bcrypt 到底怎么选 | MD5 还能用吗？密码该用 SHA-256 吗？bcrypt 和 Argon2 选哪个？本文用真实泄露案例讲清各种 Hash 算法的边界——以及最重要的：哪些场景千万不要用错。 | [阅读](https://lddi.net/zh/blog/hash-algorithms-comparison) |
| 正则表达式从零到精通：5 大场景实战与灾难性回溯陷阱 | 正则是开发者高频但易错的工具。本文从语法基础出发，覆盖邮箱/URL/IP/日志等 5 大实战场景，并深入讲解灾难性回溯——Cloudflare 2019 年全球宕机的真凶。 | [阅读](https://lddi.net/zh/blog/regex-mastery) |
| JWT 完全指南：原理、5 大安全陷阱与生产最佳实践 | JWT 用一行字符串解决了无状态认证，但也带来了一整套安全陷阱。本文从三段式结构讲到 alg=none、密钥泄露、Refresh Token 设计，把生产中真正该懂的 JWT 全讲透。 | [阅读](https://lddi.net/zh/blog/jwt-complete-guide) |

有疑问或建议欢迎 [提 Issue](https://github.com/ldddi/lddi-blog-issues/issues/new)。

---

## Posts

| Title | Summary | Link |
|-------|---------|------|
| Cloudflare Tunnel in Practice: Expose Your Home Lab Without a Public IP | No public IP, no VPS, no router port forwarding — Cloudflare Tunnel lets you publish your NAS, blog, or HomeAssistant to the internet through a single outbound connection. This guide takes you from concepts to a working deployment. | [Read](https://lddi.net/en/blog/cloudflare-tunnel-guide) |
| The Complete Guide to Building a Telegram Bot: From Creation to Deployment | A step-by-step guide to building your own Telegram bot — from registering with BotFather, choosing a framework (Python or Node.js), writing your first handler, to deploying in production. | [Read](https://lddi.net/en/blog/create-telegram-bot) |
| SSH Key Authentication Guide: Ditch Passwords, Secure Your VPS | A complete walkthrough of SSH key authentication from concepts to hands-on setup. Covers key generation, VPS passwordless login, Windows configuration, and common troubleshooting. | [Read](https://lddi.net/en/blog/ssh-key-authentication-guide) |
| HostDare vs BandwagonHost: Routes, Bandwidth, and Pricing Compared | A factual comparison of HostDare and BandwagonHost for proxy deployments — covering CN2 GIA route quality, peak-hour stability, IP blocking policies, and protocol compatibility. | [Read](https://lddi.net/en/blog/hostdare-vs-bandwagonhost-proxy) |
| Modern Domains in Practice: Registrar Choice, DNS, and Full SPF/DKIM/DMARC Setup | Buying a domain is only the beginning — picking the wrong registrar costs hundreds extra per year, missing one DNS record breaks the whole site, and skipping SPF means your emails go straight to spam. This guide covers registrar comparison, DNS records, the email anti-spam trinity, and domain security. | [Read](https://lddi.net/en/blog/domain-dns-mastery) |
| Cron Expressions from Basics to Mastery: The Logic Behind 5 Fields and the Traps to Avoid | Five fields look simple — get one wrong and your daily backup might run once a year. This guide systematically covers cron syntax, dialect differences, common mistakes, and real-world examples. | [Read](https://lddi.net/en/blog/cron-expression-mastery) |
| The Self-Hosted Stack: Run Your Own Cloud with Docker Compose | Move Google Drive, password manager, photos, notes, and monitoring onto your own server. This guide strings 10 worth-it self-hosted apps together with Docker Compose, adds a reverse proxy and backup strategy, and gives you a private cloud that's 100% yours. | [Read](https://lddi.net/en/blog/self-hosted-stack) |
| Hash Algorithms Compared: How to Choose Between MD5, SHA-1, SHA-256, and bcrypt | Can MD5 still be used? Should passwords use SHA-256? bcrypt or Argon2? This guide uses real breach incidents to map every hash algorithm to its right scenarios — and which mistakes you absolutely must avoid. | [Read](https://lddi.net/en/blog/hash-algorithms-comparison) |
| Regex from Zero to Mastery: 5 Real-World Patterns and the Catastrophic Backtracking Trap | Regex is the developer's daily bread — and a frequent source of bugs and outages. This guide covers core syntax, five real-world patterns (email, URL, IP, log parsing), and the catastrophic backtracking that took Cloudflare down globally in 2019. | [Read](https://lddi.net/en/blog/regex-mastery) |
| The Complete JWT Guide: Internals, 5 Security Pitfalls, and Production Best Practices | JWT solves stateless authentication in a single string — and brings a whole catalogue of security pitfalls with it. This guide walks the three-part structure, alg=none attacks, key leakage, refresh token design, and everything you actually need to know to use JWT in production. | [Read](https://lddi.net/en/blog/jwt-complete-guide) |

Questions or suggestions? Feel free to [open an Issue](https://github.com/ldddi/lddi-blog-issues/issues/new).
