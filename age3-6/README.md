# 3-6岁家长 2/4/7 主题下钻

本发布包由 `scripts/run-age36-deep-dive-247.mjs` 生成。

- `index.html`：可分享的静态页面。
- `age3-6-deep-dive-247-data.json`：页面对应的结构化归簇结果。

证据口径：只把评论正文作为需求证据；帖子标题、搜索词、正文只作语境和采集入口。

采样限制：TikHub 小红书 + 抖音接口；每个 seed 默认搜索第一页，每词最多 6 个帖子，每帖最多 30 条评论；采集状态和接口错误保存在 JSON 的 `sample_stats.source_health`。
