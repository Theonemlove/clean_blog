# Clean Blog

一个基于Django开发的博客系统:

- Python3.6 和 Django1.10
- MySQL储存方案
- xadmin后台管理
- ckeditor编辑器，图片上传
- Bootstrap前端模板
- RSS订阅
- 标签分类与日期归档
- 文章评论
- haystack文章内容搜索

Usage:

- 新建虚拟环境

'''
git clone git@github.com:wzyonggege/clean_blog.git
virtualenv --python=<py3path> venv
. venv/bin/activate
'''

- 数据库迁移

'''
python manage.py makemigrations
python manage.py migrate
'''

- 创建管理员
'''
python manage.py createsuperuser
'''

------
### 首页

![index](/pic/2.png)

### 详情页

![index](/pic/3.png)

### 评论发表

![index](/pic/8.png)

### 归档

![index](/pic/7.png)

### xadmin后台

![index](/pic/5.png)

### ckeditor文章编辑器

![index](/pic/1.png)

### 图片上传

![index](/pic/9.png)

