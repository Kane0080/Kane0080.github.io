# 姜凯耀的个人主页（星空宇宙风）

星空动态背景 + 可上传头像 + 思想记录 + 写作专区，全部可自己编辑。

## 文件结构

```
homepage/
├── index.html          主页（星空背景、头像、各板块）
├── articles.js         文章列表（写作文库，新增文章改这里）
├── avatar.jpg          你的头像（把一张图片命名成 avatar.jpg 放进来即可）
├── README.md           本说明
└── articles/           文章正文都放这里
    ├── sample-article.html   示例文章
    └── article-2.html        第二篇（示例）
```

## 一、怎么编辑 & 预览

1. 用记事本 / VS Code 打开 `index.html`，按 `Ctrl+F` 搜 `✏️`，改名字、简介、座右铭、思想记录、友链。
2. 改完双击 `index.html`，浏览器即可预览。

## 二、怎么设置头像

两种方式：
1. **临时上传**：直接在主页上点击圆形头像 → 从电脑选一张图片，会立刻显示（并保存在你自己浏览器里）。
2. **永久设置**（别人也能看到）：把一张图片重命名为 `avatar.jpg`，放进 `homepage` 文件夹，覆盖即可。

## 三、怎么写文章（写作专区）

1. 复制 `articles/sample-article.html`，改名为你文章的名字（比如 `articles/我的文章.html`）。
2. 打开它，改掉标题和正文。
3. 打开 `articles.js`，复制一段 `{ ... },`，填好 `title`（标题）、`date`（日期）、`summary`（摘要）、`url`（文章文件路径）。
4. 刷新主页，写作专区就会出现这篇文章，点击标题即可阅读。

> 要传很多文章？每篇文章重复上面三步即可，写作文库会自动列出所有文章。

## 四、怎么免费发布

### 方案 ① GitHub Pages（免费，学长同款）
1. 注册 [GitHub](https://github.com) 账号。
2. 新建仓库，名字必须是 `你的用户名.github.io`（如 `jiangkaiyao.github.io`）。
3. 把 `homepage` 文件夹里的**所有文件**（index.html、articles.js、avatar.jpg、articles/ 文件夹）上传到仓库。
4. 打开 `https://你的用户名.github.io` 即可访问。

### 方案 ② 绑定 eu.cc 免费域名（像学长那样）
1. 去 [gname.net](https://www.gname.net) 免费注册一个 eu.cc 域名，比如 `jiangkaiyao.eu.cc`。
2. 在 GitHub 仓库 → Settings → Pages → Custom domain 填上 `jiangkaiyao.eu.cc`。
3. 到 gname 把域名 CNAME 解析到 `你的用户名.github.io`。

### 方案 ③ 国内访问更快
- Cloudflare Pages（免费，可直接上传文件部署）。
- 腾讯云 EdgeOne Pages（国内版，国内访问最快）。

---

发布是免费的，但托管账号需要你本人注册。注册好 GitHub 后，把用户名 + Personal Access Token 发我，我可以直接帮你把主页推上线；凭证我会严格保密。
