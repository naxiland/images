# images — linyue 博客图床

为 https://www.linyue.run.place/ 供图的静态图片仓库，公开仓库，经 jsDelivr 加速。

## 目录结构

- `book-share/`：每日读书分享的封面与正文配图
- `free-games/`：每日免费游戏速递的封面与正文配图

文件命名：`YYYY-MM-DD-<简短标识>.jpg`（或原格式），例如 `book-share/2026-11-03-huozhe.jpg`。

## 引用方式

文章里用 jsDelivr 地址，不要直接用 raw.githubusercontent.com（国内访问不稳定）：

```
https://cdn.jsdelivr.net/gh/naxiland/images@main/book-share/2026-11-03-huozhe.jpg
```

注意：新图推送后，jsDelivr 需要一点时间同步，刚推完立刻访问可能 404，稍等再试。

## 规则

- 只放博客文章实际用到的图，不当通用网盘。
- 封面优先用横向宽幅图，单张尽量压到 1MB 以内。
- 换图只追加新文件、不改旧文件名，避免已发布文章的图链失效。
