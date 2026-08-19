# XHooki.github.io

围绕“纸飞机搜索资源引擎”和“纸飞机搜索群组”制作的原创 Telegram 公开资源搜索与安全指南。

## 收录配置

- 首页包含唯一标题、摘要、canonical、Open Graph 和 Schema.org 结构化数据。
- `robots.txt` 允许正常抓取并声明站点地图。
- `sitemap.xml` 可提交至百度搜索资源平台。
- 页面使用静态 HTML，正文无需 JavaScript 即可读取。

百度站点验证字符串需要登录百度搜索资源平台后取得，再添加至首页 `<head>`。提交站点地图可以帮助搜索引擎发现页面，但不能保证收录或排名。
