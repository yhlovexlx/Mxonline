**教育网站Demo**
--------------------------------------------------------------------------------------------------------------------------
### 项目结构
|目录                                    |介绍                                                                           |
|:------                                 |:--------------------                                                          |
|apps                                    |本项目应用，可以包含多个                                                       |
|** apps.course                          |** 本项目应用，课程模块                                                        | 
|**** apps.course.migrations             |**** 用于记录 models 中数据的变更。                                            | 
|**** apps.course.admin.py               |**** 映射 models 中的数据到 Django 自带的 admin 后台。                         | 
|**** apps.course.adminx.py              |**** 映射 models 中的数据到xadmin后台                                          | 
|**** apps.course.apps.py                |**** 在新的 Django 版本中新增，用于应用程序的配置。                            | 
|**** apps.course.models.py              |**** 创建应用程序数据表模型（对应数据库的相关操作）。                          | 
|**** apps.course.tests.py               |**** 创建 Django 测试                                                          | 
|**** apps.course.urls.py                |**** Django 项目的 URL 声明                                                    | 
|**** apps.course.views.py               |**** 控制向前端显示哪些数据                                                    | 
|** apps.operation                       |** 本项目应用，授课模块                                                        |
|** apps.organization                    |** 本项目应用，课程机构模块                                                    |
|** apps.users                           |** 本项目应用，用户模块                                                        |
|** apps.utils                           |** 本项目工具类                                                                | 
|media                                   |前端资源文件，存放网站图片                                                     |
|Mxonline                                |项目的容器(包名和项目名一致，也可以修改）,包含了项目的基本配置                 |
|** Mxonline._init_.py                   |** 用来告诉python，当前目录是python模块                                        |
|** Mxonline.settings.py                 |** Django 项目的配置文件，包括 Django 模块应用配置，数据库配置，模板配置等。   |
|** Mxonline.urls.py                     |** Django 项目的 URL 声明。                                                    |
|** Mxonline.wsgi.py                     |** 为 WSGI 兼容的 Web 服务器服务项目的切入点。                                 |
|static                                  |前端资源文件，存放js/css/img等                                                 |
|templates                               |模板目录,覆盖app的模板，存放html等模板文件                                     |
|manage.py                               |一个实用的命令行工具，可让你以各种方式与该 Django 项目进行交互。               |
|mxonline3.sql                           |本项目数据库脚本文件                                                           |

### xadmin创建超级管理员权限：yanghl/yanghl123
* 控制台进入到项目的manage.py文件目录
* 执行python manage.py createsuperuser后一次输入用户名和密码(8位以上数字字母)



