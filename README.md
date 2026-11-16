# 二次元游戏玩家行为分析系统 · 在线预览

Python + Vue 的二次元游戏玩家行为分析系统（玩家行为分析 + 版本反馈 + LLM 智能聊天）在线预览版。

- 在线地址：https://huangc-x.github.io/anime-game-analytics/
- 演示登录：admin / admin123
- 说明：本仓库为前端预览部署。总览 / 分群 / 漏斗 / 抽卡 / 流失 / LTV / 数据管理页面的数字，是本地后端真实运行后从数据库聚合抓取的接口数据（模拟生成的 180 天数据，阶段 7 状态）；文件导入、LLM 聊天等需要真实后端的操作在预览版中不可用。
- 源码项目：二次元游戏玩家行为分析系统（FastAPI + Vue 3，阶段 0-7 已完成）

## 源码

完整项目源码（FastAPI 后端 + Vue 3 前端，阶段 0-7）在本仓库 [`source/`](https://github.com/HuangC-X/anime-game-analytics/tree/main/source) 目录，所有人可见：

- `source/backend/` — FastAPI 后端（数据层 / ETL / 分群 / 流失 / LTV 等）
- `source/frontend/` — Vue 3 前端（10 个页面）
- 注：落地页用到的 4 张照片（frontend/public/img/*.jpg）因上传通道只支持文本文件未包含在此副本中，原图在项目原仓库内；其余文件与原仓库一致。
