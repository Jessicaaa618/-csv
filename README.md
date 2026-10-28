# CSV Check 运行说明

技术文档写作课程配套材料：用一条命令检查 CSV 表格的列名。

本仓库用于托管《CSV Check 1.0.0 运行说明》网页版，通过 GitHub Pages 发布。

## 在线阅读

https://jessicaaa618.github.io/-csv/

## 内容说明

- 工具：`check.py`（随课程实践包 `01_写作练习` 提供，仅依赖 Python 标准库）
- 作用：读取 CSV，确认表头是否包含 `id`、`name`、`score` 三列，打印七行报告
- 文档含：运行前准备、三种结果（PASS / FAIL / ERROR）对照、退出码、故障排查
- 页面为单文件 HTML，三张终端截图以 base64 内嵌，无外部依赖
- 字体：中文楷体（Kaiti SC / 楷体），西文 Calibri，代码 Consolas（含跨平台回退）

## 文件

| 文件 | 说明 |
|---|---|
| `index.html` | 文档网页版（单文件，自包含） |
| `.nojekyll` | 跳过 Jekyll 处理，确保静态文件按原样发布 |

## 本地查看

直接双击 `index.html` 用浏览器打开即可。
