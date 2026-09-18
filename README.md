# 徐杰的个人主页

面向中文教培与个人展示的静态网站，发布于 `https://wyss-520.github.io/`。

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## 修改内容

主要内容位于 `index.html`，后续可继续补充：

- 个人介绍与教培经历；
- 授课科目、目标学员和课程形式；
- 课程案例、学员反馈与内容动态；
- 邮箱、微信或其他公开联系方式。

图片放在 `assets/images/`。样式位于 `assets/css/style.css`，移动端导航脚本位于
`assets/js/main.js`。


## Publish

Create a public GitHub repository named `wyss-520.github.io`, push this directory
to its `main` branch, and select **Deploy from a branch** in
**Settings → Pages** if Pages is not enabled automatically.
