# 实习工作台

凡岛大学人才发展实习生工作记录网页，包含三个模块：

- **工作概览** — 月视图日历事件
- **AI 实践** — Skill 卡片与 AI 赋能实践报告
- **培训研习实录** — 培训课程笔记（手风琴 + 时间筛选）

仓库地址：https://github.com/Liyouyou0407/intern-dashboard

## 如何使用

1. 下载本仓库中的 [`intern-dashboard.zip`](./intern-dashboard.zip)
2. 解压压缩包
3. 双击打开其中的 `intern-dashboard.html`

无需安装、无需联网，用浏览器即可打开。

## 仓库内容

| 文件 | 说明 |
|------|------|
| `intern-dashboard.zip` | 最新完整项目压缩包（推荐下载） |

解压后通常包含：

- `intern-dashboard.html` — 单文件网页（结构 / 样式 / 数据 / 交互均内嵌）
- `README.md` / `UPDATE.md` / `SKILL.md` — 使用与维护说明（若包内有）

## 页面说明

纯静态单页，零外部依赖。所有数据写在 HTML 内的 JavaScript 变量中：

| 数据 | 对应页面 |
|------|----------|
| `CALENDAR_DATA` | 工作概览（日历） |
| `SKILLS_DATA` / `AI_REPORTS_DATA` | AI 实践 |
| `TRAINING_DATA` | 培训研习实录 |

## 以后如何更新

1. 用最新的「工作日历概览.xls」「培训内容日志.docx」更新网页内容（只改数据，不改布局）
2. 重新打包为 `intern-dashboard.zip`
3. 上传覆盖本仓库中的压缩包即可

## 作者

李凤芸 · GitHub：[@Liyouyou0407](https://github.com/Liyouyou0407)
