# Reader 书源配置

[binbyu/Reader](https://github.com/binbyu/Reader) 小说阅读器书源配置，已实测可用。

## 使用说明

1. 打开 Reader → 设置 → 书源配置 → 导入 `reader_bs.json`
2. 搜索想要的小说即可

## 书源列表

| # | 书源 | 域名 | 搜索方式 | 章节 | 正文容器 | 状态 |
|---|------|------|---------|------|---------|------|
| 1 | 平凡文学 | pksge.la | POST `searchkey=%s` | 102章 | `#booktext` | ✅ 已验证 |
| 2 | 笔书网(biqukun) | biqukun.org | GET `searchkey=%s` | 102章 | `#content` | ✅ 已验证 |
| 3 | 八一中文网(wangshuwx) | wangshuwx.com | GET `searchkey=%s` | 102章 | `#content` | ✅ 已验证 |
| 4 | 就爱文学网(92xs) | 92xs.info | GET `searchkey=%s` | 103章 | `.content` | ✅ 已验证 |

> 测试书目：《我在乱世开无双》作者 不会飞的笔

## 文件说明

- `reader_bs.json` — 4 个书源合并配置（推荐导入这个）
- `sources/` — 单书源独立配置

## 验证日期

2026-08-03
