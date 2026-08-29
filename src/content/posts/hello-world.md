---
title: 你好，世界
published: 2026-08-29
description: 这是我的第一篇博客文章
tags: ["随笔"]
category: 随笔
draft: false
---

欢迎来到我的博客！这是我用 [Fuwari](https://github.com/saicaca/fuwari) 搭建的个人博客。

之后我会在这里分享我的想法、学习和生活。

## 如何写新文章

在 `src/content/posts/` 目录下新建一个 `.md` 文件即可，例如：

```markdown
---
title: 我的新文章
published: 2026-08-29
description: 文章简介
tags: ["标签"]
category: 分类
draft: false
---

这里是正文内容。
```

也可以用命令自动创建：

```sh
pnpm new-post 我的新文章
```

写完后运行 `pnpm dev` 本地预览，`pnpm build` 构建，然后推送到 GitHub 就能自动部署上线了。