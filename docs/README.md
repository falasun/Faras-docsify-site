# 本项目概况

> git pages：https://falasun.github.io/Faras-docsify-site/#/
### 样式异常2
样式异常2

# 快速开始

（哇真的可以快速开始吗?）那 Docsify 是什么？Docsify 是一个“文档网站生成器”，专门用来把 Markdown 文件变成可以浏览的网页文档。

✅ 它有什么特点？你只要写 Markdown 文件（比如 README.md），Docsify 就能把它变成一个结构化的网页。

它不像 Hugo 那样要“编译”，而是浏览器实时渲染，所见即所得。

修改一个 .md 文件，刷新网页就看到结果，非常轻便。

👩‍💼 谁会用它？开源项目维护者：用来写项目说明文档（Docsify 官网就是 Docsify 写的）

团队内部文档站：技术文档、产品说明书、使用手册

产品经理 / 技术写作者：不需要前端开发能力，也能快速上线网页形式的说明文档

🧩 对你来说：Docsify 就是把你的产品文档变成结构化网页的“工具箱”。

# 配置

## 启动index页面
shell输入：npx docsify serve docs

## 手动运行Prettier
在项目中，如果你希望手动运行 Prettier 来格式化 Markdown 文件，可以使用以下命令：
```bash
npm run format

在package.json中有配置format命令：prettier --write \"docs/**/*.md\

# 部署


