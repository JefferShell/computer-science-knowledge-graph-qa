## 计算机学科知识图谱问答系统 README.md

### 项目简介

计算机学科知识图谱问答系统是一个基于计算机学科知识的图谱问答系统。通过知识图谱的展示和问答功能，帮助用户更加直观地理解和查询计算机学科知识。

### 主要功能

- **知识图谱展示**：可直观地查看计算机学科中的各个知识点及其之间的关联关系。
- **知识图谱问答**：支持自然语言识别的问答功能，可以自动从知识图谱中查询相关信息。
- **用户管理**：完善的用户管理功能，确保系统的安全性和用户数据的隐私性。


### 技术架构

- **后端:** Django框架 + py2neo + neo4j
- **前端:** echarts + jQuery


### 使用说明

1. 下载项目代码。 
2. 使用 `pip install -r requirements.txt` 命令安装依赖项。
3. 在项目根目录运行 `python manage.py migrate` 命令创建数据库表。
4. 使用 `python manage.py loaddata.py` 命令导入知识图谱数据。
5. 启动项目并打开浏览器访问localhost:8000。


### 联系方式

**微信号：zt745324325**