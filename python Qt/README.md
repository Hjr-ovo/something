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
 | `5_httpclient.py` | HTTP 接口测试工具（第五个练习），支持 GET/POST/PUT/DELETE，可自定义请求头和请求体 |
 | `ui/` | 存放 Qt Designer 生成的 `.ui` 界面文件 |
 | `dist/` | 存放打包后的 exe 可执行文件（`5_httpclient.exe`） |

### 5_httpclient.py 补充说明

- **功能**：图形化 HTTP 请求调试工具，可自由添加/删除请求头，发送请求并查看响应
- **开发运行**：`python 5_httpclient.py`
- **exe 打包**：使用 PyInstaller 打包，exe 位于 `dist/5_httpclient.exe`，**无需额外依赖**，双击即可运行
- **打包命令**：
  ```bash
  python -m PyInstaller --distpath "dist" --workpath "build" --add-data "ui/5.ui;." --onefile --windowed 5_httpclient.py
  ```
- **注意事项**：需配合 `ui/5.ui` 界面文件使用，若修改了 `5.ui` 需重新打包才会生效


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