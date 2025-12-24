# ModernBlog - Django 博客系统

一个现代化的博客平台，采用顶级 UI 设计风格。

## 功能特性

### 前端功能
- **首页**: 导航栏、Hero Banner、精选推荐、最新文章、热门文章、推荐作者、分类、标签云
- **文章详情**: 文章内容、目录导航、点赞/收藏、评论区、相关推荐
- **个人主页**: 用户 Banner、头像、资料、文章列表
- **设置中心**: 编辑资料、修改密码、我的收藏/点赞/浏览历史

### 后台管理
- 用户管理
- 文章管理（发布、编辑、删除、推荐）
- 分类管理
- 标签管理
- 评论管理（审核）
- 数据统计

## 快速开始

```bash
# 安装依赖
pip install -r requirements.txt

# 数据库迁移
python manage.py migrate

# 初始化数据
python init_data.py

# 启动服务
python manage.py runserver
```

## 访问地址

- 前台: http://127.0.0.1:8000/
- 后台: http://127.0.0.1:8000/admin/
- 账户: admin / admin123

## 项目结构

```
blog/
├── accounts/          # 用户模块
├── articles/          # 文章模块
├── core/              # 核心模块
├── blog_project/      # 项目配置
├── templates/         # 模板文件
├── static/            # 静态文件
└── media/             # 媒体文件
```

## 技术栈

- Django 4.2+
- SQLite (可切换 PostgreSQL)
- 原生 CSS (现代 UI)
- Vanilla JavaScript
