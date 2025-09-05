# 中南大学生存指南

## 项目简介

「中南大学生存指南」是一个面向中南大学本科生的非官方指导手册，旨在帮助中南大学的学生更好地规划学习生活，找到人生方向。本项目受到了「上海交通大学生存手册」和「清华大学飞跃计划」等优秀项目的启发，希望能够为中南大学的学生提供类似的帮助。

## 项目目标

- 提供学习经验分享，帮助学生更高效地学习专业知识
- 分享校园生活技巧，让新生快速适应大学生活
- 整理就业与升学相关资源，为学生未来发展提供参考
- 收集各专业课程评价与学习建议，帮助学生合理规划课程
- 汇总校内外资源，让学生充分利用大学时光

## 项目结构

```
.
├── docs/                # 文档目录
│   └── chapters/        # 各章节内容
├── website/             # 网站源码
│   ├── src/             # 网站源代码
│   └── public/          # 网站静态资源
├── assets/              # 项目资源文件（图片、PDF等）
├── CONTRIBUTING.md      # 贡献指南
└── README.md            # 项目说明
```

## 内容大纲（初步）

1. **新生指南**
   - 入学准备
   - 校园生活
   - 学习方法
   - 社团活动

2. **专业学习**
   - 各学院专业介绍
   - 课程评价与建议
   - 学习资源推荐
   - 考试经验分享

3. **科研与竞赛**
   - 科研入门指南
   - 常见竞赛介绍
   - 实验室资源
   - 优秀案例分享

4. **实习与就业**
   - 简历与面试
   - 行业分析
   - 校招信息
   - 职业规划

5. **考研与出国**
   - 考研经验
   - 留学申请
   - 语言考试
   - 奖学金信息

6. **生活与成长**
   - 心理健康
   - 时间管理
   - 社交技巧
   - 个人成长

## 本地使用指南

### 获取项目

1. **克隆仓库**：
   ```bash
   git clone https://github.com/BREKOJI/CentralSouthUniversity_survial_instructions.git
   cd CentralSouthUniversity_survial_instructions
   ```

2. **直接下载**：
   - 访问项目GitHub页面
   - 点击"Code"按钮，选择"Download ZIP"
   - 解压下载的文件到本地目录

### 浏览文档

1. **直接阅读**：
   - 可以直接在`docs/chapters/`目录下阅读Markdown格式的原始文档
  
2. **访问github部署的网页**：
   - 访问[https://brekoji.github.io/CentralSouthUniversity_survial_instructions/website/public/](https://brekoji.github.io/CentralSouthUniversity_survial_instructions/website/public/)，可直接使用

3. **本地部署+本地网页浏览**：
   - 进入网站目录：`cd website`
   - 启动本地HTTP服务器：
     ```bash
     # 使用Python（推荐）
     python -m http.server 8000 --directory public
     
     # 或使用Node.js
     npx serve public
     ```
   - 在浏览器中访问 `http://localhost:8000`

4. **离线PDF**：
   - 项目发布页面提供PDF版本下载（计划中）

## 如何参与

我们欢迎所有中南大学的学生、校友以及教职工参与到本项目中来。您可以通过以下方式参与：

1. **提交内容**：分享您的学习经验、生活技巧或者其他有价值的信息
2. **修改完善**：帮助我们修正错误、更新过时的信息
3. **技术支持**：协助网站开发、文档排版等工作

具体的参与方式请参考 [CONTRIBUTING.md](./CONTRIBUTING.md) 文件。

## 免责声明

本项目内容均由贡献者自愿提供，仅供参考，不代表中南大学官方立场。我们会尽力保证内容的准确性，但不对因使用本指南造成的任何后果负责。

## 版权声明

本项目采用 [知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议（CC BY-NC-SA 4.0）](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 进行许可。

## 联系我们

如有任何问题或建议，请通过以下方式联系我们：

- 项目仓库：[[GitHub地址](https://github.com/BREKOJI/CentralSouthUniversity_survial_instructions)]
- 电子邮件：[[联系邮箱](934974681@qq.com)]

---

**中南大学生存指南** - 助力每一位中南学子成长与发展
