# 数学建模竞赛学习手册（离线单文件网站）

一个**零依赖、双击即开**的数学建模备赛学习站，纯原生 HTML / CSS / JavaScript 实现，全部内容打包在单个 `index.html` 内，无需联网、无需安装任何框架。

## 在线访问

GitHub Pages 在线地址：

> https://lhy-frighter.github.io/math-modeling-handbook/

仓库地址：https://github.com/lhy-frighter/math-modeling-handbook

## 本地使用

下载 `index.html`，用任意现代浏览器（Edge / Chrome / Firefox）直接打开即可。学习进度、笔记、答题记录通过浏览器 localStorage 保存在本机，不上传任何数据。

## 内容结构（35 个视图）

- **封面学习仪表盘**：掌握度、已读章节、判题 / 自测统计，进度自动保存
- **11 个算法专题章节、69 张可展开算法卡**：评价决策、数学规划、启发式优化、图论路径、回归分析、时间序列、有监督分类、聚类降维、神经网络、统计检验、机理建模与数值方法；每张卡含核心公式、应用场景、建模步骤、要点与易错
- **真题思路分析专题**：4 个历年真题全流程拆解（为什么用这个算法、备选方案对比、解题顺序、代码架构）
- **训练与查漏**：37 题场景判题训练、12 题公式自测、2014–2024 真题反查矩阵、120 条术语词典
- **实战工具**：算法选型向导、Python/MATLAB 库速查、论文配图与图表指南、代码报错手册、一页纸可打印速查、三条学习路径
- **学习体验**：四档字号、逐页本地笔记与笔记总览、按掌握度 / 错题自动生成的复习冲刺台、明暗双主题、移动端适配

## 技术说明

- 单文件、原生 JS hash 路由（`#/home`、`#/m1` 等），无任何外部依赖与网络请求
- 数据仅存于浏览器 localStorage：`mcm-checks` / `mcm-quiz` / `mcm-drill` / `mcm-notes` / `mcm-fs` / `mcm-theme`
- 公式使用 Unicode 表示，离线可读

## 自行部署到 GitHub Pages

1. 仓库保持公开（Public）
2. Settings → Pages → Source 选择 `main` 分支、根目录 `/(root)`
3. 等待约 1 分钟，即可通过 `https://用户名.github.io/仓库名/` 访问
