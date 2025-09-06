# 项目运行说明

使用`python3.9`

## 安装

使用pip安装：
```bash
pip install -r requirements.txt
```
如果你没有pip，使用如下方式安装：  
**MacOS / Linux** 电脑，终端下执行: 

```bash
curl http://peak.telecommunity.com/dist/ez_setup.py | python
curl https://bootstrap.pypa.io/get-pip.py | python
```

## 数据库配置

将数据库文件`djangoblog_database.sql`导入数据库中，  
或使用`Navicat`数据库工具进行配置


## 开始运行

终端执行：
```bash
./manage.py runserver --insecure
```

浏览器打开: http://127.0.0.1:8000/  就可以看到效果了。 


## 示例账户

```
Superuser：Marsk
Password：Marsk327

```
