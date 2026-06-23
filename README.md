# OpenAudit Hub Demo

A static, phone-friendly interview demo for OpenAudit Hub.

OpenAudit Hub is a self-hosted website governance platform inspired by tools such as Siteimprove. The full private project combines open-source scanners for accessibility, SEO, performance, link checking, content quality, and keyword analysis.

This public repository intentionally contains only a static demo page and a safe summary dataset from a public website scan. It does not include Docker services, raw scan reports, databases, credentials, or customer data.

## Current demo dataset

The live demo currently presents an aggregated audit snapshot for:

- `truckhardware.com.au`
- 3 Lighthouse page summaries
- 20 Pa11y page checks
- 279 grouped accessibility findings

## Demo scope

- Dashboard overview
- Accessibility score and grouped issues
- SEO overview and keyword suggestions
- Content quality examples
- Analytics placeholder
- Safe simulated scan replay
- Mobile and iPad friendly layout

## Full project architecture

The full OpenAudit Hub stack uses:

- Flask portal
- Docker Compose
- Lighthouse
- Pa11y
- LinkChecker
- crawler and page inventory
- content quality rules
- YAKE keyword extraction
- background scan workers

## Notes

The public demo is presentation-safe. It is designed for interviews and quick walkthroughs on phone, iPad, or desktop.

---

# OpenAudit Hub 演示版

这是 OpenAudit Hub 的静态面试演示页面，适合手机和 iPad 打开。

OpenAudit Hub 是一个自托管的网站治理平台，灵感来自 Siteimprove。完整私有项目整合了无障碍、SEO、性能、死链检查、内容质量和关键词分析等开源工具。

这个公开仓库只包含静态演示页面和一个安全的公开数据快照，不包含 Docker 服务、原始扫描报告、数据库、账号密码或客户数据。

## 当前演示数据

当前演示页面展示的是公开网站 `truckhardware.com.au` 的汇总审计快照，包括：

- 3 个 Lighthouse 页面摘要
- 20 个 Pa11y 页面检查摘要
- 279 个分组后的无障碍问题

## 演示内容

- Dashboard 总览
- Accessibility 分数和问题分组
- SEO 总览和关键词建议
- Content Quality 示例
- Analytics 占位演示
- 安全的模拟扫描流程
- 手机和 iPad 友好布局
