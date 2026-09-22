# Toutiao News Backend

基于 FastAPI 开发的新闻头条后端项目。本项目主要用于学习和实践 FastAPI 框架的核心功能，包括路由管理、请求与响应处理、数据校验、数据库操作以及 RESTful API 开发。项目实现了新闻分类管理、新闻列表查询、新闻详情获取等基础功能，并通过 SQLAlchemy 与 MySQL 数据库进行数据持久化。

## 技术栈

- Python 3
- FastAPI
- SQLAlchemy
- Pydantic
- MySQL
- Uvicorn

## 功能介绍

- 新闻分类管理
- 新闻列表展示
- 新闻详情查询
- RESTful API 接口开发
- 数据库持久化存储
- 自动生成 Swagger 接口文档

## 安装与运行

## 进入项目目录

cd toutiao_news_backend

## 创建并激活虚拟环境

python -m venv venv

source venv/bin/activate

## 安装项目依赖

pip install -r requirements.txt

## 启动项目

uvicorn main:app --reload

## 接口文档

项目启动后可通过以下地址访问 FastAPI 自动生成的接口文档：

http://127.0.0.1:8000/docs

## 学习收获

通过本项目学习并实践了以下内容：

FastAPI 项目结构设计
APIRouter 路由管理
Pydantic 数据验证
SQLAlchemy ORM 操作
MySQL 数据库应用
RESTful API 设计规范
Git 与 GitHub 项目管理

## 作者
Yinghao Xiao
