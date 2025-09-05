# 中南大学生存指南网站

## 项目简介

这是「中南大学生存指南」项目的网站部分，用于展示和分享指南内容。网站采用简单的HTML、CSS和JavaScript构建，便于维护和扩展。

## 目录结构

```
.
├── public/             # 网站静态资源和HTML文件
│   ├── css/           # 样式文件
│   ├── js/            # JavaScript文件
│   ├── chapters/      # 各章节HTML页面
│   └── index.html     # 网站首页
├── src/               # 网站源代码（如果使用构建工具）
├── config.json        # 网站配置文件
└── README.md          # 本文件
```

## 开发指南

### 本地开发

1. 克隆仓库到本地
2. 进入网站目录：`cd website`
3. 使用任意HTTP服务器启动网站，例如：
   - Python: `python -m http.server 8000 --directory public`
   - Node.js: `npx serve public`
4. 在浏览器中访问 `http://localhost:8000`

### 添加新章节

1. 在 `public/chapters/` 目录下创建新的HTML文件
2. 参考现有章节页面的结构和样式
3. 在 `config.json` 文件中添加新章节的信息
4. 在首页的章节导航部分添加新章节的链接

### 修改样式

1. 编辑 `public/css/style.css` 文件
2. 如需添加新的样式规则，请遵循现有的命名和组织方式

### 添加交互功能

1. 编辑 `public/js/main.js` 文件
2. 如需添加新的JavaScript功能，请遵循现有的代码风格和组织方式

## 部署指南

### 静态网站托管

本网站可以部署到任何静态网站托管服务，如GitHub Pages、Netlify、Vercel等。

1. 将 `public` 目录中的内容上传到托管服务
2. 配置域名和其他设置
3. 访问部署后的网站

### 自托管

如果需要在自己的服务器上托管：

1. 将 `public` 目录中的内容上传到Web服务器的根目录
2. 配置Web服务器（如Nginx、Apache）指向该目录
3. 确保正确设置MIME类型和文件权限

## 贡献指南

欢迎对网站进行改进和扩展。请参考项目根目录下的 [CONTRIBUTING.md](../CONTRIBUTING.md) 文件了解如何贡献。

## 许可证

本项目采用 [知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议（CC BY-NC-SA 4.0）](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 进行许可。