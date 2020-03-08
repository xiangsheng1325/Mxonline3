# Mxonline3 在线教育(Django3.0 + Xadmin 后台管理+ Ueditor 富文本编辑器)

[![Build Status](https://travis-ci.org/mtianyan/hexoBlog-Github.svg?branch=master)](https://travis-ci.org/mtianyan/hexoBlog-Github)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

使用Python3.7与Django3.0开发的在线教育平台网站: http://mxonline.mtianyan.cn

> 已测试xadmin,  DjangoUeditor Django3.0下功能可用。 如有3.0使用时触发Bug,可请进群联系。欢迎加入 funpython.cn QQ群:211599322

## 开始使用之前
1. 确保mysql已创建相应的数据库
```sql
CREATE DATABASE mxonline3;
```
2. 修改Mxonline3/Mxonline3/settings.py  将DATABASES属性的password改为与本机一致

## 如何开始使用？

```shell
git clone https://github.com/mtianyan/Mxonline3.git
cd Mxonline3
pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

use the address: http://127.0.0.1:8000/

## TODO:


## 致谢 [原版视频课程地址:](https://coding.imooc.com/learn/list/78.html)

## 关于我

**欢迎star项目！谢谢！你的关注支持是我继续分享前进的动力**
