<div align="center">
  <img src="public/logo.png" alt="domaindex" height="64" />

  <h1>domaindex — 批量域名可用性查询工具</h1>

  <p>输入关键词，实时查询 100+ 后缀的注册情况 — 基于 RDAP，无需注册账号</p>

  [![在线使用](https://img.shields.io/badge/在线使用-domaindex.io-0A7CFF)](https://domaindex.io)
  [![支持后缀](https://img.shields.io/badge/TLD-100%2B-brightgreen)](https://domaindex.io/tlds)
  [![无需注册](https://img.shields.io/badge/无需注册-免费使用-success)](https://domaindex.io)

  [English](./README.md) · [中文](./README.zh.md)
</div>

<br />

<div align="center">
  <img src="./screenshot.png" alt="domaindex 批量域名查询工具" width="800" />
</div>

<br />

## domaindex 是什么？

**[domaindex.io](https://domaindex.io)** 是一款免费的批量域名可用性查询工具。输入任意关键词 — 品牌名、项目名或个人ID — 立即查看该词在 **100+ 域名后缀**下的注册情况，结果实时返回。

与传统的 WHOIS 工具逐条查询不同，domaindex 同时发起最多 **30 个并发 RDAP 请求**，每个注册局响应后立即显示结果。你不需要等所有查询完成，可用域名会实时出现在列表中。

```
关键词: acme

acme.com    → 已注册   (注册于 1995-04-28)
acme.io     → 可注册 ✓
acme.ai     → 已注册
acme.app    → 可注册 ✓
acme.dev    → 可注册 ✓
acme.co     → 已注册
...
```

## ✨ 功能特性

**⚡ 并发查询 100+ 域名后缀**
`.com`、`.net`、`.org`、`.io`、`.ai`、`.app`、`.dev`、`.co`、`.me` 等 100+ 后缀一次性全部查完，无需逐个输入。

**📡 基于 RDAP 的实时结果**
结果随各注册局响应实时流式返回，无需等待最慢的注册局。快速后缀几秒内出结果。

**🔗 结果链接可分享**
关键词和已选后缀会编码在 URL 中。把链接发给团队，对方直接打开即可看到相同的搜索结果。

**🎛️ 自定义后缀列表**
只选你关心的后缀，偏好设置自动保存在浏览器本地 — 无需登录账号。

**🛒 一键跳转到注册商**
可注册的域名直接附带 Namecheap、Porkbun、GoDaddy 的购买链接，无需手动复制粘贴。

**📋 域名详情面板**
点击任意结果查看注册日期、到期日期、注册商和域名服务器 — 均来自实时 RDAP 数据。

**🔒 零门槛使用**
无需注册，无需邮箱，无埋点追踪。输入关键词，直接开始。

## 🎯 适合哪些人使用？

| 用户群体 | 使用场景 |
|---|---|
| **创业者 / 品牌主** | 同时检查 `.com`、`.io`、`.ai` 等热门后缀，抢在竞争对手前锁定域名 |
| **独立开发者** | 项目上线前一次性确认名称在各主流后缀下是否可用 |
| **域名投资者** | 几秒内扫描某关键词在数十个后缀下的注册状态 |
| **品牌/命名顾问** | 在命名工作坊中实时查询可用性 |
| **仍在一个个手输域名的你** | 有更快的方法 |

## ❓ 常见问题

**什么是批量域名查询工具？**
批量域名查询工具可以同时检测多个域名是否已被注册。与逐条查询 `mybrand.com`、`mybrand.io`、`mybrand.ai` 不同，domaindex 并发查询所有后缀，结果实时返回，大幅节省时间。

**什么是 RDAP？它和 WHOIS 有什么区别？**
RDAP（注册数据访问协议）是 WHOIS 的现代替代方案。它返回结构化 JSON 数据而非纯文本，查询速度更快、更稳定，也不容易被限速。domaindex 所有可用性查询均使用 RDAP，无需抓取页面。

**domaindex 支持多少个域名后缀？**
domaindex 支持 **100+ 个域名后缀**，包括常用通用顶级域（`.com`、`.net`、`.org`、`.io`、`.ai`、`.app`、`.dev`）、国家/地区域（`.co`、`.me`、`.uk`）以及新通用顶级域。完整列表见 [domaindex.io/tlds](https://domaindex.io/tlds)。

**domaindex 免费吗？**
是的，域名可用性查询完全免费，无需注册。高级功能（项目保存、API 访问等）可在付费计划中使用，详见 [domaindex.io/pricing](https://domaindex.io/pricing)。

**查询结果准确吗？**
domaindex 直接请求各 TLD 官方 RDAP 注册局，数据新鲜度和准确性与注册局本身一致。部分国家域未开放 RDAP 接口，该后缀可能无法返回结果。

**能把查询结果分享给团队吗？**
可以。关键词和已选后缀始终编码在 URL 中，直接复制链接发送即可，对方无需账号或安装任何软件。

## 🔗 相关链接

- 🌍 **免费在线使用**: [domaindex.io](https://domaindex.io)
- 📖 **后缀浏览**: [domaindex.io/tlds](https://domaindex.io/tlds)
- 💰 **定价方案**: [domaindex.io/pricing](https://domaindex.io/pricing)
- 🗺️ **产品路线图**: [domaindex.io/roadmap](https://domaindex.io/roadmap)
- 📝 **博客**: [domaindex.io/blog](https://domaindex.io/blog)
- 🐦 **Twitter / X**: [@ruguodev](https://x.com/ruguodev)

---

© 2025 domaindex · 保留所有权利 · [domaindex.io](https://domaindex.io)
