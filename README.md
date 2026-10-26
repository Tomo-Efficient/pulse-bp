# Pulse · 商业计划书（网页版）

**线上地址：<https://tomo-efficient.github.io/pulse-bp/>**

2026-10-26 版，单文件静态站点，无外部依赖（不加载 CDN 字体或图片）。

- `index.html` — 网页版 BP：16 章、深/浅主题、打印导出、响应式
- `pulse-business-plan.pdf` — 18 页 PDF 导出件

## 更新

```bash
./deploy.sh               # 上传全部文件
./deploy.sh index.html    # 只更新单个文件
```

本机 git push 到 github.com 不稳定（TLS 中断），脚本改走 GitHub Contents API；
Pages 通常 30 秒内重建，进度见 <https://github.com/Tomo-Efficient/pulse-bp/actions>。

## 说明

内部讨论材料，已设置 `noindex` 与 `robots.txt`，但链接本身可公开访问。
