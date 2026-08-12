# duanchu.github.io

Duanchu Wang 的个人学术主页（简介 + 论文）。

本地预览：用浏览器打开 `index.html`，或在本目录执行 `python3 -m http.server 8000`。

## 发布到 GitHub Pages

这个环境没有你的 GitHub 登录，所以不能替你推送。请在自己电脑上操作：

`https://duanchu.github.io` 只能由 GitHub 用户名 **duanchu** 发布。请先确认 [github.com/duanchu](https://github.com/duanchu) 是你的账号。

1. 登录 **duanchu** 账号，新建公开仓库，名字必须是 `duanchu.github.io`
2. 在本目录执行：

```bash
git init
git add .
git commit -m "Add academic homepage"
git branch -M main
git remote add origin https://github.com/duanchu/duanchu.github.io.git
git push -u origin main
```

3. 打开仓库 Settings → Pages，Source 选 `main` 分支、目录 `/`，保存
4. 稍等一两分钟，访问 https://duanchu.github.io

如果 `duanchu` 不是你的账号，短地址无法使用。那时应在 `DuanchuWang` 账号下建仓库 `DuanchuWang.github.io`，地址为 https://duanchuwang.github.io 。
