# Buen Camino

一本自九世纪起就在路上的书，陪你跟着真实的历史人物读朝圣之路，并排出自己的行程。

这是静态网站，无需构建，把本目录放到仓库根目录并开启 GitHub Pages 即可。
页面默认带 noindex；正式公开前删除 index.html 里的 robots 标记。

## 地图数据

- 海岸线和国界：Natural Earth，经 world-atlas 转换（公有领域）。
- 河流：Natural Earth 10m rivers（公有领域）。
- 地形：从 Natural Earth 风格的晕渲地形图（basemap-data 附带）提取高原和山地，重绘成旧地图式的山形符号。
- 每日终点：按主流攻略的常见分段整理，坐标是城镇中心的近似位置。

## 语言

有中文和英文两个版本。默认按浏览器语言打开，封面底部和左侧面板可以切换，也可以在链接后加 `?lang=en` 或 `?lang=zh` 直接打开对应版本。英文文本在 `i18n/` 的生成结果 `i18n_en.js` 里。

English edition: add `?lang=en` to the link, or switch on the cover.
