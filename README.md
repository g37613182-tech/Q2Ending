# 季度复盘 · 一场生产方式的进化

Q2 季度复盘单页网页。围绕四条并行目标线（O1 机制化生产 / O2 醒图活人感 / O4 方法论沉淀 / O3 影响力·新技术）与关键节点的相互反哺，呈现「Workflow → Skill → Agent」的演进暗线。

## 本地预览

```bash
cd quarter-review-site
python3 -m http.server 8891
# 打开 http://localhost:8891/index.html
```

## 目录

- `index.html` — 单页站点（结构 / 样式 / 交互一体）
- `assets/` — 真实架构图与自托管字体
  - `aeea-agent-arch.png` — AEEA Agent 系统架构
  - `aeea-hot-chain-matrix.png` — 追热链路全流程矩阵
  - `fonts/` — Big Shoulders / Instrument Sans / Geist Mono

纯静态，无外部依赖，可直接部署到任意静态托管（GitHub Pages 等）。
