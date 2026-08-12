# manga-sources

J2ME 漫画阅读器（MangaReader）的源仓库。

## 结构

- `index.json` — 源列表（应用内"从源仓库添加"读取此文件）
- `sources/*.json` — 每个源的规则定义（JSON 规则引擎格式）

## 添加新源

在 `sources/` 下放一个规则 JSON（格式见 `sources/baozi.json`），并在 `index.json` 的 `sources` 数组里登记 key/name/desc。

## 分发

jsdelivr CDN：`https://cdn.jsdelivr.net/gh/coj211/manga-sources@main/index.json`

当前源：再漫画、包子漫画、MangaDex（2026-08）
