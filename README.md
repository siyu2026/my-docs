# my-docs

# MkDocs 静态文档自动部署项目

## 项目简介

本项目基于 MkDocs + Material 主题搭建静态文档站点，搭配 GitHub Actions 实现代码推送后自动构建、自动部署到 GitHub Pages。修改 Markdown 文档并推送到远程仓库，流水线会自动重新发布网页，验证持续自动部署效果。

## 在线网站地址

https://siyu2026.github.io/my-docs/

## 实践报告入口

[查看完整实践报告](./report/README.md)

## 本地预览方式

```bash
# 安装依赖
pip install -r requirements.txt

# 本地启动预览服务
mkdocs serve
```
