# CLAUDE.md

## 项目概述
单文件前端英语词汇练习应用，所有代码在 index.html 中。
无后端、无构建工具、无第三方依赖。

## 技术栈
- 原生 HTML5 / CSS3 / Vanilla JS (ES6+)
- state 对象集中管理状态
- LocalStorage 持久化错题本
- Web Speech API 发音

## 硬约束
- 保持单文件结构
- 不引入任何框架或 CDN 依赖
- 不擅自重构已有逻辑
- 新增功能做增量，不改已有功能
- 改动前先说明方案，再给代码

## 关键函数
- startGame() → 初始化一轮
- renderQuestion() → 渲染当前题目
- chooseAnswer() → 处理答题逻辑
- showResults() → 结果页
- renderMistakeBook() → 错题本
- recordMistake() / removeMistake() → 错题管理