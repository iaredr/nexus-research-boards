# Pricegraphy learn gallery · 截图清单

目标页：`nexus-research-boards/boards/2026-10-28-pricegraphy-learn-gallery.html`  
图片部署路径：`boards/assets/learn-gallery/`（本目录 `assets/` 为采集暂存）

## 书 · 封面（必需）

| 文件名 | 书 |
|---|---|
| `book-gold-morrow.png` | 《黃金：從宇宙誕生到金融市場…》東尼·李·莫羅 |
| `book-illustrated-money.png` | 《圖解貨幣簡史》維達利 |
| `book-secret-history-gold.png` | 《黃金如何驅動世界？》弗里斯比 |
| `book-great-devaluation.png` | 《大貶值》亞當·巴拉塔 |
| `book-wallet-world-history.png` | 《錢包裡的世界史》宮崎正勝 |
| `book-not-just-0050.png` | 《不只0050：黃金&白銀ETF…》元大投信 |
| `book-precious-metals-guide.png` | 《貴金屬領航》連尉宏 |
| `book-wall-street-gold.png` | 《華爾街頂尖操盤手的黃金投資法》+市場先生 |

## 书 · 内页关键图（可选，建议每本 1–2 张）

命名：`{slug}-interior-01.png`、`{slug}-interior-02.png`  
例如：`book-gold-morrow-interior-01.png`（淘金熱/价签类彩图）、`book-illustrated-money-interior-01.png`（金本位一页图）、`book-not-just-0050-interior-01.png`（实体/ETF 对照表）。

内页进页后可在 HTML 卡片中追加第二图槽；当前骨架只绑封面 `slug.png`。

## 站上案例（部分已有）

| 文件名 | 状态 | 说明 |
|---|---|---|
| `case-homepage.png` | ✅ 已从 moneyvisualized-screenshots 拷入 | 首页 |
| `case-topics.png` | ✅ | Guides/topics |
| `case-home-full.png` | ✅ 备用 | 全页长截 |
| `case-social-card.png` | ✅ | 社媒卡 |
| `case-fractional-premium.png` | ⏳ 待截 / 或用示意图 | 小规格溢价表 |
| `case-melt-gap.png` | ⏳ | 熔值 vs 到手价 |
| `case-piece-vs-gram.png` | ⏳ | 一口价验算 |

## 落盘后

```bash
cp /workspace/pricegraphy-learn-gallery/assets/*.png \
  /workspace/nexus-research-boards/boards/assets/learn-gallery/
cp /workspace/nexus-research-boards/boards/assets/learn-gallery/*.png \
  /workspace/pricegraphy-board/assets/learn-gallery/
# 再 push GitHub Pages（等截图齐 + 人工确认）
```
