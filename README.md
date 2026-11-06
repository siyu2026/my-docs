# my-docs

## 项目简介

本项目基于 MkDocs + Material 主题搭建静态文档站点，搭配 GitHub Actions 实现代码推送后自动构建、自动部署到 GitHub Pages。修改 Markdown 文档并推送到远程仓库，流水线会自动重新发布网页，验证持续自动部署效果。

## 在线网站地址

https://siyu2026.github.io/my-docs/

## 实践报告入口

[查看完整实践报告](./report/README.md)

# 本地预览方式

```bash
# 1. 创建并激活虚拟环境（Git Bash）
python -m venv .venv
source .venv/Scripts/activate

# 2. 安装依赖
pip install -r requirements.txt

# 3. 本地启动预览服务（屏蔽MkDocs2.0警告）
NO_MKDOCS_2_WARNING=1 mkdocs serve
```

启动后访问 `http://127.0.0.1:8000/my-docs/` 预览网站；修改文档会自动刷新，按 `Ctrl + C` 停止服务。
