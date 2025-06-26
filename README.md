# 哒哒的个人博客 🚀

一个现代化的个人博客静态网站，展示AI实战设计师的专业技能和作品。

## 📋 项目简介

这是一个使用纯HTML、CSS和JavaScript构建的响应式个人博客网站，采用现代化设计风格，完全适配移动端设备。

## ✨ 功能特性

- 🎨 **现代化设计**：采用渐变色彩和卡片式布局
- 📱 **响应式设计**：完美适配桌面、平板和手机设备
- 🎯 **用户体验**：平滑滚动、悬停效果、动画过渡
- 📧 **联系表单**：支持表单验证和提交反馈
- 🎪 **互动元素**：技能展示、统计数据动画、博客卡片
- 🍔 **移动导航**：汉堡菜单支持移动端导航

## 🛠️ 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **样式**: CSS Variables, Flexbox, Grid Layout
- **字体**: Inter字体系列
- **图标**: Font Awesome 6.0
- **托管**: 可部署到GitHub Pages、Netlify等静态网站托管服务

## 📁 项目结构

```
dadamy/
├── index.html          # 主页面文件
├── styles.css          # 样式文件
├── script.js           # JavaScript交互文件
└── README.md           # 项目说明文件
```

## 🚀 快速开始

### 本地运行

1. **克隆项目**
   ```bash
   git clone https://github.com/kuzu008/dadamy.git
   cd dadamy
   ```

2. **启动本地服务器**
   ```bash
   # 使用Python (推荐)
   python3 -m http.server 8000
   
   # 或使用Node.js
   npx serve .
   
   # 或使用PHP
   php -S localhost:8000
   ```

3. **访问网站**
   打开浏览器访问 `http://localhost:8000`

### 部署到GitHub Pages

1. 在GitHub仓库中进入 `Settings` > `Pages`
2. 选择 `Deploy from a branch`
3. 选择 `main` 分支和 `/ (root)` 目录
4. 保存设置，等待部署完成
5. 访问 `https://kuzu008.github.io/dadamy/`

## 🎨 自定义配置

### 修改个人信息

编辑 `index.html` 文件中的以下部分：

- **个人信息**：姓名、职业、简介
- **技能展示**：更新技能图标和名称
- **博客文章**：修改文章标题、分类和摘要
- **联系方式**：更新邮箱、社交媒体链接

### 自定义样式

在 `styles.css` 中修改CSS变量来改变主题色彩：

```css
:root {
    --primary-color: #6366f1;     /* 主色调 */
    --secondary-color: #10b981;   /* 辅助色 */
    --accent-color: #f59e0b;      /* 强调色 */
}
```

## 📱 响应式断点

- **桌面端**: > 1024px
- **平板端**: 768px - 1024px  
- **手机端**: < 768px
- **小屏手机**: < 480px

## 🌟 主要特色

### AI主题设计
- 专为AI实战设计师量身定制
- 突出机器学习、深度学习等专业技能
- 展示AI项目和设计作品

### 现代化交互
- 平滑的页面滚动动画
- 悬停效果和过渡动画
- 数字统计的动态显示
- 表单验证和反馈通知

### 优秀的性能
- 纯静态文件，加载速度快
- 优化的图片和资源
- 兼容所有现代浏览器

## 🤝 贡献指南

欢迎提交Issue和Pull Request来改进这个项目！

1. Fork 这个仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个Pull Request

## 📄 许可证

这个项目使用MIT许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 📞 联系方式

- **作者**: 哒哒
- **职业**: AI实战设计师
- **项目链接**: [https://github.com/kuzu008/dadamy](https://github.com/kuzu008/dadamy)

## 🙏 致谢

- [Font Awesome](https://fontawesome.com/) - 图标库
- [Google Fonts](https://fonts.google.com/) - Inter字体
- [GitHub Pages](https://pages.github.com/) - 静态网站托管

---

⭐ 如果这个项目对你有帮助，请给个Star支持一下！ 