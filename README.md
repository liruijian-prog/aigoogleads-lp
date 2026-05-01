# aigoogleads.liruijian.com

这是一个面向 SaaS 与 Google Ads 场景的静态站，包含：

- 账户配置模板导航页
- PLG SaaS Google Ads 账户配置模板
- B2B 线索型 SaaS Google Ads 账户配置模板
- 面向 `coveauto.ai` 这类“配置/优化型 SaaS”的账户配置模板
- 基于 `coveauto.ai` 公开定位整理的首批投放方案页

## 页面列表

- `index.html`
- `plg-saas-google-ads-template.html`
- `b2b-lead-gen-google-ads-template.html`
- `google-ads-config-saas-for-google-ads-saas.html`
- `coveauto-google-ads-launch-plan.html`

## 本地预览

```bash
cd /Users/work-0110/google-ads-account-templates
python3 -m http.server 4326
```

访问：

```text
http://127.0.0.1:4326
```

## 线上发布建议

推荐使用 GitHub Pages，并绑定自定义域名：

- 仓库：建议新建 `liruijian-prog/aigoogleads-lp`
- GitHub Pages Source：`GitHub Actions`
- `CNAME`：`aigoogleads.liruijian.com`
- DNS：为 `aigoogleads` 添加 `CNAME -> liruijian-prog.github.io`

注意：截至 2026-05-01，本地检查发现 `aigoogleads.liruijian.com` 还没有 DNS 解析，所以即使代码推送完成，公网访问也要等 DNS 生效。
