# Changhao Liu — GitHub Pages 个人主页

这是一个无需构建工具或第三方依赖的单页学术主页，可以直接上传到：

`https://github.com/llllbhw/llllbhw.github.io`

## 上传前必须修改

打开 `index.html`，全文替换以下两处占位内容：

1. `YOUR_EMAIL@example.com` → 你的公开邮箱（文件中出现 5 次）
2. `YOUR_AFFILIATION` → 你的学校或单位（文件中出现 2 次）

OpenReview 明确要求主页同时显示姓名和邮箱，因此邮箱不能保留占位符。

## 上传方法

1. 进入 GitHub 仓库 `llllbhw/llllbhw.github.io`。
2. 将本文件夹中的 `index.html` 和 `.nojekyll` 上传到仓库根目录。
3. 若仓库中已有同名 `index.html`，用本文件覆盖它。
4. 提交后等待约 1–5 分钟，然后访问 `https://llllbhw.github.io/`。
5. 确认页面能看到 “Changhao Liu” 和你的真实邮箱。
6. 将 `https://llllbhw.github.io/` 填入 OpenReview 的 **Homepage URL**。

## 为什么要覆盖旧的 index.html

当前公开主页会跳转到 `/love`，但该路径返回 404。新的 `index.html` 不包含这个跳转，上传到仓库根目录后即可恢复主页。

## 本地预览

直接双击 `index.html` 即可预览；也可以在该目录运行：

```bash
python3 -m http.server 8000
```

然后打开 `http://127.0.0.1:8000/`。
