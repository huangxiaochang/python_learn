python基础知识
=============

# 虚拟环境安装
1.在一台电脑上可以安装多个版本的python
2.使用pip install virtualenv来下载虚拟环境(所有python版本公用)
3.进入项目根目录，然后通过virtualenv来安装依赖不同版本python的虚拟环境
```
如安装python2的虚拟环境
virtualenv -p 'python2的安装目录' '虚拟环境名'

如安装python3的虚拟环境
virtualenv -p 'python3的安装目录' '虚拟环境名'
```
4.从根目录激活虚拟环境
'虚拟环境文件夹名'\Scripts\activate
如：env\Scripts\activate

5.安装项目库
可以使用pip install '库名' 来安装相应的库
或者根据项目中的依赖库的文件来安装(如果项目存在库依赖文件:如requirements.txt)
pip install -r requirements.txt

6.产生项目所需库文件目录
 pip freeze > requirements.txt
 
7.退出虚拟环境
 deactivate指令即可退出虚拟环境


