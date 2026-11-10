# 浪漫至死不渝 · 李然

一个纯静态的单文件网站，保留了原网站由多国语言“我爱你”组成的心形动画，并做了两处调整：

1. 完全移除背景音乐、音乐播放按钮及相关脚本。
2. 在爱心中间加入白色发光的名字「李然」。

## 使用

直接用浏览器打开 `index.html` 即可。

如果要在本机预览：

```powershell
python -m http.server 8787 --directory "D:\codex\liran-heart"
```

然后访问 `http://127.0.0.1:8787/`。

## 发布

把 `index.html` 上传到任意静态网站托管即可（GitHub Pages、Netlify、Vercel、对象存储等都支持）。

## 修改名字

在 `index.html` 中找到：

```html
<h1 class="name">李然</h1>
```

替换成需要的文字即可。
