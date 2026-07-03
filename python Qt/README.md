# 🐍 Python Qt 学习项目

> 本目录用于记录 PySide6（Qt for Python）桌面应用开发的学习过程。

## 简介

这是我学习 Python Qt 桌面应用开发的练习项目合集，使用 **PySide6**（Qt 的官方 Python 绑定）进行开发。每个文件是一个独立的练习程序，从基础到进阶逐步实践。

📖 课程来源：[https://www.byhy.net/](https://www.byhy.net/)

## 环境要求

- Python 3.8+
- PySide6

```bash
pip install PySide6
```

## 文件列表

| 文件 | 说明 |
|------|------|
| `first.py` | 第一个练习程序——简易薪资统计工具界面，包含按钮和文本编辑框的基本布局 |
| `2.py` | 在 first.py 基础上实现统计按钮功能，按薪资 20000 划分显示上下人员名单 |
| `3.py` | 在 2.py 基础上使用类封装界面和功能，提升代码组织性 |
| `4.py` | 使用 Qt Designer 设计的 UI 文件加载界面，实现界面与逻辑分离 |
| `ui/` | 存放 Qt Designer 生成的 `.ui` 界面文件 |


## 运行方式

```bash
cd "python Qt"
python 文件名.py
```

例如：

```bash
python first.py
```

---

*本目录持续更新中...*