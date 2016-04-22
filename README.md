# Flask_Blog


> 当前框架  Flask+SQLite+*Markdown+*Frozen+Bootstrap+ckeditor

> 环境 ubuntu + nginx + gunicorn 


### 2016年04月22日 【第四个试行版本  Alpha_v0.4.22】

* 修复文章编辑错误
* 更新 uwsgi 的脚本以及 nginx参数脚本
* 添加安装脚本 install.py， 自动创建数据库，根据输入创建站点，用户
* 添加 run.sh 启动脚本
* 添加 clean.sh 清理脚本，删除*～ 、*.pyc 、 数据库文件


### 2016年04月21日 【第三个试行版本  Alpha_v0.4.21】

* 修复文章编辑错误
* 采用gunicorn作为wsgi服务器
* 提供flup uwsgi gunicorn 的nginx参数脚本
* 添加基本数据库脚本，ins.sh
* ！在文章编辑保存过程中，有可能跳出，请先备份……没搞好……sorry
，正在找原因

### 2016年04月18日 【第二个试行版本  Alpha_v0.4.18】

* ckeditor编辑器添加上传功能
* 提供文章导出为JSON  /admin/outputjson
* 预留inputjson 接口
* 显示系统当前线程，使用内存
* 提供uwsgi、nginx初级脚本
* 部分未传……添加……


### 2016年04月18日 【第一个试行版本  Alpha_v0.0.1】

* 能够创建、编辑、删除文章
* 用户登陆
* 完成基本功能，整合ckeditor编辑器
* 预留outputjson、inputjson
* 测试ckeditor上传

##关于

* @作者：[糖果果|Sugarguo](http://www.sugarguo.com/)
* ![糖果果|Sugarguo](http://7xignn.com1.z0.glb.clouddn.com/LOGO.png)
* @version    	Alpha_v0.4.22
* @copyright    [糖果果|Sugarguo](http://www.sugarguo.com/)

