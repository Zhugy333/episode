---
version: alpha
colors:
  ink: "#172033"
  navy: "#184B76"
  canvas: "#F4F6F8"
  surface: "#FFFFFF"
  line: "#DCE3EA"
  muted: "#667085"
  success: "#2F6D5B"
  warning: "#9A6415"
typography:
  display:
    fontFamily: "Iowan Old Style, Songti SC, STSong, serif"
  sans:
    fontFamily: "PingFang SC, Microsoft YaHei, Noto Sans SC, system-ui, sans-serif"
  mono:
    fontFamily: "SFMono-Regular, Consolas, Liberation Mono, monospace"
rounded:
  card: "14px"
  control: "8px"
spacing:
  page: "32px"
  section: "24px"
components:
  card: { border: "1px solid #DCE3EA", shadow: "none" }
  button: { radius: "8px", primary: "#184B76" }
---

## Overview

这是面向中文用户的决策工作簿：像一份可反复推敲的分析表，而不是替人下结论的仪表盘。留白、秩序和可读数字优先。

## Colors

以纸张般的浅灰为画布，墨蓝只用于推进、当前步骤和数据重点；绿色和赭黄仅表达正向及需要留意的信息。

## Typography

标题克制使用宋体风格来强调“审慎思考”；正文使用中文系统无衬线；分数、权重和排序使用等宽字体，便于横向比较。

## Layout

桌面端最大宽度 1180px，采用单列工作流，数据区允许独立横向滚动。移动端操作区保持自然页面滚动，主要操作按钮全宽。

## Elevation & Depth

静态卡片使用细边框，不使用阴影。仅在悬停时以轻微背景变化提示可操作内容。

## Shapes

小圆角承载输入和卡片；不用胶囊形按钮，也不使用渐变。

## Components

按钮有实心、描边、文字三种强调度。错误和破坏性操作使用明确文案与确认对话框。所有保存反馈由同一状态条承载。

## Do's and Don'ts

应把数字、假设和限制说清楚；不应把排名包装成命令或确定性承诺。尊重减少动态效果的系统设置。
