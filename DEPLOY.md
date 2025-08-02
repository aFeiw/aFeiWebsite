# 网站部署说明

## GitHub Pages 部署

### 1. 准备工作
- 确保你的GitHub账号已创建
- 将代码推送到GitHub仓库

### 2. 启用 GitHub Pages
1. 进入你的GitHub仓库
2. 点击 `Settings` 标签
3. 在左侧菜单中找到 `Pages`
4. 在 `Source` 部分选择 `Deploy from a branch`
5. 选择 `main` 分支和 `/ (root)` 文件夹
6. 点击 `Save`

### 3. 自定义域名（可选）
如果你想使用自定义域名：
1. 在 `Custom domain` 字段中输入你的域名
2. 在你的域名提供商处添加CNAME记录
3. 点击 `Save`

### 4. 访问网站
部署完成后，你的网站将在以下地址可用：
- `https://你的用户名.github.io/仓库名/`
- 如果设置了自定义域名，则使用你的域名

## 文件结构
```
aFeiWebsite/
├── index.html          # 首页
├── resume.html         # 简历页
├── works.html          # 项目作品页
├── blog.html           # 技术博客页
├── contact.html        # 联系页面
├── README.md           # 项目说明
├── DEPLOY.md           # 部署说明
└── assets/             # 静态资源
    ├── images/         # 图片资源
    ├── styles/         # CSS样式
    ├── js/            # JavaScript文件
    └── icons/         # 图标文件
```

## 更新内容
- 更新了所有页面的元数据和SEO信息
- 展现了5年工作经验的专业形象
- 完善了技术栈和项目经验
- 更新了文档地址为GitHub Pages
- 优化了页面内容和用户体验

## 注意事项
- 确保所有图片资源路径正确
- 检查所有链接是否有效
- 测试网站在不同设备上的显示效果
- 定期更新内容和项目经验 