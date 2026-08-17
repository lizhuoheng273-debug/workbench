# 秋招工作台（公开快照）

李卓衡的 2027 秋招工作台公开静态站点。

## 访问

- 工作台：`https://lizhuoheng273-debug.github.io/workbench/`

这是从本地自包含工作台（`秋招工作台/frontend/index.html`）导出的阶段性快照，
数据内嵌于页面（`window.__WB__`），纯静态、无任何后端依赖。

## 结构

```
workbench-pages/
├── index.html   # 秋招工作台（自包含单文件）
├── .nojekyll    # 禁用 Jekyll 处理
└── README.md
```

## 更新

本地重新扫描生成后，运行 `秋招工作台/发布到Pages.bat` 即可把最新快照推送上线。
