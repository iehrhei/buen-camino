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

## 授权 / License

| 内容 | 授权 |
|---|---|
| 代码：`index.html` 里的 HTML、CSS、JavaScript，以及生成脚本 | [MIT](LICENSE) |
| 原创内容：中英文文字、幽灵的叙述、封面（`cover2.webp`、`cover2_en.webp`）、皮革和纸张纹理、地形符号，以及整理出来的路线、住宿和安全资料 | [CC BY-NC-SA 4.0](LICENSE-CONTENT)，署名“Buen Camino, by Rhei Tan” |
| Rhei Tan 的藏书票（`assets/bookplate.webp`） | 保留所有权利，不在上述授权内 |
| “Buen Camino”“Rhei Tan”两个名字 | 不授权用来冒充原作或暗示原作者认可 |

可以学、可以改、可以分享；改编后要用同样的协议发布，并且不能商用。想商用请联系作者。

### 第三方素材

这些不归本项目授权，按各自的条款使用：

- **字体**：EB Garamond、Noto Serif SC、UnifrakturMaguntia，均为 SIL Open Font License 1.1，授权文本在 `fonts/` 里。
- **地图数据**：海岸线、国界、河流和地形底图来自 Natural Earth，公有领域；海岸线和国界经 world-atlas 转换。
- **古地图和古籍插图**：作品本身因年代久远已进入公有领域。
  - 埃茨劳布的朝圣路线图（约 1500 年）：`etz.jpg`、`platealps.jpg`、`platebohemia.jpg`、`platenur.jpg`
  - 1495 年朝圣指南的扉页木刻：`woodcut.jpg`
  - 瓦赫纳尔的加利西亚海图（约 1588 年）及其局部：`chart.jpg`、`chartcrop.jpg`、`ship1.png`、`ship2.png`、`monster.png`、`compass.png`、`rose.png`
  - 其余小插图（`boar.png`、`cattle.png`、`town1.png`、`town2.png`、`mounds.png`、`mounds2.png`、`hillsA.png`、`hillsB.png`）来自同一批古地图。
  - 扫描件的收藏机构和链接还在补充中。如果你是某份扫描件的权利人并有异议，请开 issue。
- **事实和数字**：统计、价格、时刻等来自页面上标注的各个来源，链接都在对应条目里。

Code is MIT. Original text and images are CC BY-NC-SA 4.0 (attribute “Buen Camino, by Rhei Tan”). The bookplate is all rights reserved. Fonts are OFL 1.1; map data is Natural Earth (public domain); historical maps and woodcuts are public-domain works, with scan provenance still being documented.
