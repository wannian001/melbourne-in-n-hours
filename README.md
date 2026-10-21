# Melbourne in N Hours · 墨尔本，几个小时

**Live demo / 在线演示: https://wannian001.github.io/melbourne-in-n-hours/**

[English](#english) · [中文](#中文)

## English

A trip planner for short-stay visitors to Melbourne who only have a few free hours here and there
(between conference sessions, before a train or a flight). The home page splits each free day into
morning, afternoon and evening: drag a ready-made walk (mostly the City of Melbourne's own
self-guided walks) or a single place into a part of a day, or press +. Each day page then works out
the best visiting order, opening hours, street busyness and the route on a 2D / 3D map, and every
place, walk and day shows about how long it takes and how tiring it is.

Work in progress for GEOM90007 Information Visualisation (University of Melbourne), Group 24,
Semester 2 2026. Please do not reuse it for coursework.

The page runs the group's R Shiny app entirely in your browser with [shinylive](https://posit-dev.github.io/r-shinylive/)
(webR). The first visit downloads about 130 MB and can take 20–60 seconds; later visits are faster.

- Data: City of Melbourne Open Data (pedestrian counts, landmarks, self-guided walks, 2023 building
  footprints, toilets, drinking fountains; CC BY), Vicmap Transport (DataVic, CC BY 4.0), opening hours
  from each place's official website. Map tiles © OpenStreetMap contributors.
- Tableau embedding helper: `tableau-in-shiny-v1.2.R` from GEOM90007 Week 8.
- AI use: the app was built with AI assistance (Claude, Anthropic).
- This repository only holds the built page; the source is in the group's private repository.

## 中文

给短暂停留墨尔本、只有零碎空闲时间的游客用的行程规划（比如会议间隙、赶火车或航班之前）。首页把每个空闲日分成
上午、下午、晚上：把一条现成路线（大多是墨尔本市政府的官方步行路线）或单个地点拖进某一格，或者点 +。
每天的页面再排出最好的参观顺序，核对开放时间和街上人流，在 2D / 3D 地图上画出路线；每个地点、每条路线、
每一天都标出大概要多久、累不累。

墨尔本大学 GEOM90007 信息可视化课程第 24 组的小组作业，还在制作中（2026 年第二学期）。请勿用于课程作业。

页面用 [shinylive](https://posit-dev.github.io/r-shinylive/)（webR）把小组的 R Shiny 程序整个放在浏览器里运行。
第一次打开要下载约 130 MB，需要 20–60 秒，之后会快一些。

- 数据：墨尔本市政府开放数据（行人计数、地标、官方步行路线、2023 年建筑轮廓、公共厕所、饮水点；CC BY），
  Vicmap Transport（DataVic，CC BY 4.0），各地点官网的开放时间。底图 © OpenStreetMap contributors。
- Tableau 嵌入：GEOM90007 第 8 周课上的 `tableau-in-shiny-v1.2.R`。
- AI 使用：程序在 AI（Anthropic 的 Claude）辅助下完成。
- 这个仓库只放生成好的网页；源代码在小组的私有仓库里。
