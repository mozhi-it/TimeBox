# 时间盒子(timebox) - 极简的待办事项管理

一个功能完整、界面精美的现代化待办事项管理应用，支持任务管理、进度追踪、数据统计和主题切换等功能。

![Preview](https://img.shields.io/badge/Version-1.0.0-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)

## ✨ 主要特性

### 📋 主要功能
- **任务管理**：创建、编辑、删除、标记完成任务
- **优先级设置**：支持高、中、低、无优先级分类
- **分类管理**：为任务设置不同分类标签
- **截止日期**：设置和追踪任务截止时间
- **进度追踪**：实时显示任务完成进度
- **统计面板**：今日任务、本周任务、逾期任务等数据统计
- **可视化图表**：直观的任务分布和完成情况展示
- **优先级分布**：不同优先级任务的数量统计
- **本地存储**：数据自动保存在浏览器本地
- **数据持久化**：刷新页面数据不丢失

## 🛠️ 技术栈

- **前端框架**：原生 JavaScript (Vanilla JS)
- **CSS框架**：Tailwind CSS
- **图标库**：Font Awesome 6.5.1
- **存储技术**：LocalStorage API
- **动画效果**：CSS3 Animations & Transitions

## 🔧 自定义配置

### 主题颜色
应用支持深色主题，可在CSS中自定义颜色方案：

```css
/* 深色主题主色调 */
body.dark {
    background-color: #0f1419 !important;
}

/* 自定义优先级颜色 */
.priority-high { border-left: 4px solid #ef4444; }
.priority-medium { border-left: 4px solid #f59e0b; }
.priority-low { border-left: 4px solid #10b981; }
```

### 分类标签
可以在JavaScript中修改默认分类：

```javascript
categories: ['工作', '学习', '生活', '健康', '娱乐'],
```

## 🌟 核心亮点

1. **单文件应用**：所有功能集成在一个HTML文件中，无需额外依赖
2. **现代化UI**：采用最新的设计趋势，界面美观易用
3. **完整功能**：涵盖任务管理的所有核心功能
4. **性能优异**：原生JavaScript实现，运行流畅
5. **跨平台**：支持所有现代浏览器
6. **离线可用**：纯前端实现，无需网络连接

欢迎提交 Issue 和 Pull Request 来改进这个项目！

**Made with ❤️ using HTML, CSS & JavaScript**
