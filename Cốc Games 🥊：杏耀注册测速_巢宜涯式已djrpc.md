杏耀注册测速【Q-——333307——】杏耀注册测速【 辋芷《888yx●vip》 】
杏耀注册测速【Q-——333307——】杏耀注册测速【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

还在羡慕别人的技术博客？其实搭建一个完全属于自己的博客，比你想的简单得多——免费、无服务器、还能自定义主题。今天这篇教程，手把手教你用 GitHub Pages + Hexo 从零开始，30分钟上线你的第一个技术博客。

 为什么选择 Hexo + GitHub Pages？

- 完全免费：托管在 GitHub，无需购买服务器和域名
- 极速访问：静态页面加载快，国内可配合 CDN 加速
- Markdown 写作：专注内容，不用折腾排版
- SEO 友好：天然适合搜索引擎收录，便于分享技术笔记

 第一步：环境准备（5分钟）

1. 安装 [Node.js](https://nodejs.org/)（LTS 版本即可）
2. 安装 [Git](https://git-scm.com/)
3. 注册 GitHub 账号并创建仓库，命名格式：`你的用户名.github.io`

 第二步：安装 Hexo 并初始化（5分钟）

打开终端，执行以下命令：

```bash
npm install hexo-cli -g
hexo init my-blog
cd my-blog
npm install
hexo server
```

浏览器访问 `http://localhost:4000`，看到默认页面就说明环境OK了。

 第三步：部署到 GitHub Pages（10分钟）

1. 修改 `_config.yml` 文件中的 `deploy` 配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

2. 安装部署插件并推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

首次部署可能需要配置 GitHub 的 PAT（个人访问令牌），按提示操作即可。

 第四步：选择主题与自定义（10分钟）

推荐几个高星主题：
- NexT：经典简洁，功能全面
- Fluid：现代风格，支持暗色模式
- Butterfly：颜值控首选，动画流畅

主题安装方式十分简单，以 NexT 为例：

```bash
npm install hexo-theme-next
```

然后在 `_config.yml` 中修改 `theme: next` 即可。别忘了阅读主题文档，个性化调整导航栏、侧边栏、评论系统等。

 第五步：写第一篇博客并提交

创建新

```bash
hexo new post "我的第一篇技术博客"
```

用 Markdown 语法在 `source/_posts/` 下编辑内容，然后重新生成并部署：

```bash
hexo clean && hexo generate && hexo deploy
```

访问 `https://你的用户名.github.io` 就能看到你的博客啦！

 提升 SEO 与流量的小技巧

- 安装 `hexo-generator-sitemap` 生成站点地图
- 每篇文章设置合理的标题、标签和分类
- 提交网址到 Google Search Console 和百度站长平台
- 添加 `description` 和 `keywords` 前两段内自然融入

 遇到问题怎么办？

部署失败？页面空白？别慌，按顺序排查：

1. 终端执行 `hexo d` 看报错信息
2. 检查仓库是否命名为 `用户名.github.io`
3. 确认 GitHub Pages 服务已在仓库 Settings 中开启
4. 清空浏览器缓存重新访问

互动时间：你打算用博客写哪方面的内容？技术笔记、面试总结还是生活随笔？有搭建疑问欢迎在评论区留言，看到都会回。如果觉得教程有用，点个 在看/点赞 支持一下，让更多朋友学会搭建自己的博客。

---

编辑搜图（此处为示意，可替换为你自己的博客截图）

---
本文步骤清晰，适合新手。如有疏漏欢迎指正，共同进步。建议收藏，下次搭建直接照做。

相关推荐：

https://github.com/millerangelica0965/agndnq/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E6%9D%8F%E8%80%80%E4%B8%BB%E7%AE%A1%E5%BC%80%E6%88%B7_%E8%8B%8F%E7%A1%AC%E6%B7%B3%E8%82%A1%E7%98%ABxrrzn.md

<img src="https://i.postimg.cc/6pSNh5x9/xingyao1-00011.png" />

相关推荐：

https://github.com/millerangelica0965/agndnq/commit/bfeee655429fd04eb0c3ff56f527bd2151d43f83

<img src="https://i.postimg.cc/FRX52WKj/xingyao1-00014.png" />
相关推荐：

https://github.com/blackerika5/qjtnuo/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%9D%8F%E8%80%80%E4%B8%BB%E7%AE%A1%E6%B3%A8%E5%86%8C_%E6%95%A2%E8%BF%9C%E6%9E%B7%E8%97%95%E7%A5%B7xwciu.md

<img src="https://i.postimg.cc/V69Q1qS2/xingyao1-00015.png" />
相关推荐：

https://github.com/blackerika5/qjtnuo/commit/6895f5906e1226428136a6828dc72e1ec887d7bd

<img src="https://i.postimg.cc/m2m4tydL/xingyao1-00005.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
