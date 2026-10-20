# 智慧水利平台架构和开发 · 课程作业

本仓库用于提交《智慧水利平台架构和开发》课程的平时作业与期末项目。每次作业放在独立目录中，包含作业说明、源代码和所需资源。

## 仓库结构

```text
jiagoukaifa_work/
├── README.md               # 课程介绍与作业目录
├── homework-01/            # 第一次作业：HTML 与 CSS 基础
│   ├── README.md           # 作业要求、实现说明与查看方式
│   ├── index.html          # 太阳系行星数据页面
│   ├── styles.css          # 外部样式表
│   └── images/             # 本地行星图片
├── homework-02/            # 第二次作业（预留）
│   └── README.md
└── final-project/          # 期末项目（预留）
    └── README.md
```

## 作业目录

| 编号 | 作业内容 | 说明 | 状态 |
| --- | --- | --- | --- |
| 01 | HTML 页面结构与 CSS 基础布局 | [作业说明](homework-01/README.md) · [页面源码](homework-01/index.html) | 已完成 |
| 02 | 第二次作业 | [预留目录](homework-02/README.md) | 未开始 |
| 期末 | 课程综合项目 | [预留目录](final-project/README.md) | 未开始 |

第一次作业以太阳系行星数据为主题，包含表格与合并单元格、图片与链接、Flex 思考题、酷炫盒子及四个基础布局练习。

## 查看作业

1. 下载或克隆仓库。
2. 用浏览器打开 `homework-01/index.html`，查看第一次作业。
3. 保留同目录的 `styles.css` 和 `images/`，保证样式和图片正常加载。

第一次作业不需要安装依赖。也可在仓库根目录运行：

```bash
python3 -m http.server 8000
```

然后在自己的浏览器中访问 `http://localhost:8000/homework-01/`。

GitHub 上的 HTML 文件链接展示的是源码；下载到本地后用浏览器打开，才能查看页面效果。

## 后续作业约定

- 平时作业按 `homework-01`、`homework-02`、`homework-03` 的顺序编号。
- 每个目录的 `README.md` 记录该次作业的要求、文件说明和运行方式。
- 图片、样式等资源保存在对应作业目录内，使用相对路径引用。
- 新增作业后更新上方的作业目录；期末项目统一放入 `final-project/`。
