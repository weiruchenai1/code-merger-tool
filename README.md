# 📁 智能文件夹代码合并工具

一个强大的在线工具，可以将整个项目文件夹的代码合并到一个格式化的 Markdown 文档中。支持可视化文件树选择，让代码整理和分享变得轻松简单。

## ✨ 功能特点

- 🚀 **拖拽上传**：支持拖拽整个文件夹，自动遍历所有子目录
- 🌳 **可视化文件树**：直观的树形结构显示所有文件和文件夹
- 🎯 **灵活选择**：点击文件夹可排除/包含整个目录，点击文件可单独控制
- 🧠 **智能过滤**：自动排除 `node_modules`、`.git`、日志文件等无关内容
- 📊 **实时统计**：显示文件数量、大小等统计信息
- 🎨 **语法高亮**：自动识别文件类型并添加相应的代码块语法
- 📱 **响应式设计**：支持桌面和移动设备
- 🔒 **隐私安全**：所有处理都在浏览器本地完成，不上传到任何服务器

## 🚀 在线使用

访问：[https://weiruchenai1.github.io/code-merger-tool](https://weiruchenai1.github.io/code-merger-tool)

## 💻 本地使用

1. 克隆仓库：
```bash
git clone https://github.com/weiruchenai1/code-merger-tool.git
cd code-merger-tool
```

2. 直接打开 `index.html` 文件即可使用（无需安装任何依赖）

## 📖 使用说明

### 基本步骤
1. **上传项目**：拖拽或选择整个项目文件夹
2. **设置项目名称**：工具会自动识别，也可手动修改
3. **选择文件**：在文件树中点击选择需要包含的文件和文件夹
4. **生成文档**：点击"生成代码文档"按钮
5. **下载保存**：下载生成的 Markdown 文件

### 文件选择技巧
- 🗂️ **点击文件夹**：包含/排除整个文件夹下的所有文件
- 📄 **点击文件**：单独包含/排除某个文件
- ✅ **全选**：选择所有文件
- ❌ **全不选**：取消所有选择
- 🔄 **重置选择**：恢复到智能默认设置

### 自动排除的文件类型
- 依赖目录：`node_modules`、`.git`、`dist`、`build`
- 临时文件：`*.log`、`*.tmp`、`*.cache`
- 系统文件：`.DS_Store`、`Thumbs.db`
- 隐藏文件和二进制文件

## 📂 输出格式

生成的 Markdown 文档包含：

```markdown
# 项目名称 代码文档

生成时间：2024-XX-XX XX:XX:XX
包含文件数量：XX

---

## 📁 项目目录结构
```
项目名称/
├── 📁 src/
│   ├── 📄 index.js
│   └── 📄 utils.js
└── 📄 README.md
```

---

## 📄 项目名称\src\index.js
```javascript
// 文件内容
console.log('Hello World');
```

## 📄 项目名称\README.md
```markdown
# 项目说明
这是一个示例项目
```
```

## 🌟 适用场景

- **代码审查**：将整个项目代码整理成文档供他人审查
- **技术分享**：制作技术教程或代码示例文档
- **项目归档**：将项目代码保存为可读性强的文档格式
- **AI 助手**：为 ChatGPT、Claude 等 AI 助手准备完整的项目上下文
- **代码备份**：以文档形式备份重要代码片段

## 🛠️ 技术栈

- **纯前端实现**：HTML5 + CSS3 + JavaScript
- **文件处理**：File API + FileReader API
- **拖拽上传**：HTML5 Drag & Drop API
- **无依赖**：不需要任何外部库或框架

## 🤝 贡献

欢迎提交 Issues 和 Pull Requests！

### 开发建议
1. Fork 本仓库
2. 创建特性分支：`git checkout -b feature/new-feature`
3. 提交更改：`git commit -am 'Add new feature'`
4. 推送分支：`git push origin feature/new-feature`
5. 提交 Pull Request

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)

## 🙏 致谢

感谢所有使用和贡献这个项目的开发者！

---

如果这个工具对你有帮助，请给个 ⭐ Star 支持一下！