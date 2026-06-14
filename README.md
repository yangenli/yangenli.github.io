# 个人主页 / Personal Homepage

这是我的个人主页项目。这个文件夹**专门用来管理这一个网站**,不放其他项目。

## 🌐 网址
**https://yangenli.github.io**

## 📁 项目说明
- 技术:纯 HTML/CSS(单文件,样式内嵌在 `index.html` 里,无需任何构建工具)
- 主页内容:英文
- 托管:GitHub Pages(免费)
- GitHub 仓库:`yangenli/yangenli.github.io`(分支 `main`,路径 `/`)
- 本地位置:`D:\OneDrive - University of Iowa\Desktop\yangenli.github.io`

## 📄 文件
- `index.html` — 网页本身(改内容就改这个文件,里面有注释指引)
- `README.md` — 本说明文件
- `.git/` — 版本与远程信息(别手动改)

## ✏️ 如何修改内容
1. 用编辑器打开 `index.html`
2. 按里面的注释(`<!-- ===== ... ===== -->`)改:
   - 头像、名字、一句话简介(tagline)
   - About 段落
   - Projects 项目卡片
   - Contact 联系方式 / 链接
3. 保存

## 🚀 如何发布更新(让线上网站生效)
在本文件夹里依次运行:
```
git add .
git commit -m "说明这次改了什么"
git push
```
推送后 GitHub Pages 会**自动重新构建,约 1~2 分钟后线上更新**。
（或者直接对 Claude 说「帮我更新网页」，它会帮你推送。）

## 🛠️ 环境备注
- GitHub CLI (`gh`) 已安装,但不在 PATH 里,完整路径:`C:\Program Files\GitHub CLI\gh.exe`
- 已用 `gh` 登录 GitHub 账号 `yangenli`,git push 可直接使用
- 本文件夹在 OneDrive 中会自动云端备份;注意**不要在 OneDrive 网页端去删改 `.git` 文件夹**,以免同步冲突

## 💡 给未来的 Claude / 自己的提示
- 想新建**别的**网站/项目 → 另建文件夹 + 另建 GitHub 仓库,别混进这里
- 本地文件夹搬家不影响线上网址,网址永远是 https://yangenli.github.io
