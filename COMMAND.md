#新建django project
django-admin.py startproject project-name
#新建django app命令
django-admin.py startapp app-name (or) python manage.py startapp app-name
#同步数据库
python manage.py syncdb
#(django1.7.1及以上版本需要使用以下命令)
python manage.py makemigrations
python manage.py migrate
#运行django项目，不加port默认为8000
python manage.py runserver port
#ex: python manage.py runserver 8080
#清空数据库
python manage.py flush
#创建超级管理员
python manage.py createsuperuser
#修改管理员密码
python manage.py changepassword username
#导出数据
python manage.py dumpdata appname > appname.json
#导入数据
python manage.py loaddata appname.json
#进入django项目命令终端
python manage.py shell
#进入数据库命令行
python manage.py dbshell