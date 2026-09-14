# 震韧智感 QuakeSense · 展示页

线上地址：https://bcl200n.github.io/quakesense-exhibition/

单页静态网站，无构建步骤、无外部字体与脚本依赖（国内网络可直接打开）。唯一的外部嵌入是哔哩哔哩播放器。

## 目录

```
index.html              全部页面结构、样式与脚本
assets/
  sim-xian.mp4 / .jpg   西安全人口疏散情景回放（静音循环，约 1 MB）与封面帧
  watch.mp4 / .jpg      “震觉”手表 watchOS 模拟器实录（已去除背景音乐）
  *.jpg                 实证图片（西昌 WebGIS、InSAR、安宁河情景、凉山人口、南宁路网、手表功能）
  qr.png                本页二维码（指向上方线上地址，已解码校验）
  fonts/qs-serif.woff2  标题用衬线字体子集（Noto Serif SC，OFL 1.1，见同目录 LICENSE.txt）
```

## 更新

改完 `index.html` 后提交并推送到 `main`，GitHub Pages 通常一两分钟内生效。

若修改了任何标题文字（`h1`–`h3` 或左上角字标），需要重新生成字体子集，否则新增的字会回退到系统字体。

## 口径

页面上的城市情景、推演回放与推定避险点均为研究口径，已在图注中逐一标明；不构成官方地震预警、烈度评定或应急预案。
