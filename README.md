# 积分打卡

一款功能丰富的积分打卡应用，帮助用户养成良好习惯，通过打卡获得积分，支持连续打卡、积分兑换、数据备份等功能。

## 项目描述

积分打卡是一款基于 React + TypeScript 的现代化习惯养成应用。用户可以创建任务、每日打卡、积累积分，并通过积分兑换奖励。应用包含连续打卡系统、补卡功能、数据备份等特性，采用精美橙色主题设计，提供流畅的用户体验。

## 功能特性

- 每日打卡 - 完成任务获得积分，支持取消打卡
- 任务管理 - 创建固定任务（每天自动出现）和临时任务（仅当日有效）
- 连续打卡 - 记录连续打卡天数，断签后可花费50积分续签
- 连续奖励 - 每连续打卡7天额外获得10积分奖励
- 截止时间 - 可为任务设置截止时间，超过时间无法打卡
- 星期选择 - 固定任务可设置仅在指定星期执行
- 积分兑换 - 使用积分兑换奖励，记录兑换历史
- 统计图表 - 查看每日、每周、每月打卡统计数据
- 历史记录 - 查看所有打卡记录
- 数据备份 - 支持导出和导入数据备份
- 任务排序 - 按积分或类型排序任务
- 动画效果 - 打卡时的积分浮动动画

## 技术栈

- React 18
- TypeScript
- Tailwind CSS 3
- Vite 6
- Zustand（状态管理）
- Lucide React（图标库）
- React Router DOM（路由）
- LocalStorage（数据持久化）

## 快速开始

### 安装依赖

```bash
npm install
```

### 开发模式

```bash
npm run dev
```

### 构建生产版本

```bash
npm run build
```

### 预览生产版本

```bash
npm run preview
```

## 项目结构

```
src/
├── components/          # 组件目录
│   ├── AnimatedNumber.tsx   # 数字动画组件
│   ├── BarChart.tsx         # 柱状图组件
│   ├── Empty.tsx            # 空状态组件
│   ├── Layout.tsx           # 布局组件
│   ├── Modal.tsx            # 弹窗组件
│   ├── PointsCard.tsx       # 积分卡片组件
│   └── SettingsSection.tsx  # 设置区域组件
├── hooks/               # 自定义 Hooks
│   └── useTheme.ts          # 主题 Hook
├── lib/                 # 工具函数
│   └── utils.ts             # 通用工具函数
├── pages/               # 页面组件
│   ├── Exchange.tsx         # 积分兑换页面
│   ├── History.tsx          # 历史记录页面
│   ├── Home.tsx             # 首页
│   ├── Stats.tsx            # 统计页面
│   └── Tasks.tsx            # 任务管理页面
├── App.tsx              # 应用入口组件
├── main.tsx             # 应用主入口
├── store.ts             # Zustand 状态管理
├── types.ts             # TypeScript 类型定义
├── utils.ts             # 通用工具函数
└── index.css            # 全局样式
```

## 许可证

MIT License
