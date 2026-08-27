# PartialDifferentialEquations

偏微分方程（PDE）课程资料仓库 — 姜礼尚教材笔记与习题。

## Structure

```
PartialDifferentialEquations/
├── main.tex
├── 00-Course/              # 课程信息 / 大纲 / 课程地图
├── 01-Textbooks/
│   └── 00-姜礼尚/          # 教材：姜礼尚《偏微分方程》
│       ├── main.tex
│       ├── 01-Notes/       # 笔记（5 章 × 节 × 小节）
│       └── 02-Homework/    # 习题（镜像笔记结构）
├── 02-Template/            # NotesTemplate / HomeworkTemplate
├── 03-Figures/             # 00-姜礼尚 配图
├── 04-References/          # references.bib
└── Settings/               # PackageSet / EnvironmentSet
```

## Chapters（姜礼尚）

<div align="center">

| 章 | 内容 | 页 |
|:---:|:---:|:---:|
| 第一章 | 方程的导出和定解条件 | P1 |
| 第二章 | 波动方程 | P31 |
| 第三章 | 热传导方程 | P108 |
| 第四章 | 位势方程 | P169 |
| 第五章 | 二阶线性偏微分方程的分类 | P221 |

</div>

## Figures

<p align="center">
  <img src="03-Figures/SYSU%20%26%20PDE.png" width="100%" alt="SYSU and PDE" />
</p>

<p align="center">
  <img src="03-Figures/SYSU%20%26%20PDE%20ASC%20Banner.png" width="100%" alt="SYSU and PDE ASC Banner" />
</p>

<p align="center">
  <img src="03-Figures/coming-soon.PNG" width="100%" alt="Coming soon" />
</p>

## Latex Playground Preview

The selected latex playground pages are available as refreshed PDF extracts.

<div align="center">

| Page | PDF |
|:---:|:---:|
| Page 10 | [main-page-10.pdf](03-Figures/latex-playground-pages/main-page-10.pdf) |
| Page 11 | [main-page-11.pdf](03-Figures/latex-playground-pages/main-page-11.pdf) |

</div>

## Course Architecture

<p align="center">
  <img src="pde_course_architecture.drawio.svg" width="100%" alt="PDE Course Architecture" />
</p>

## Build

```bash
cd 01-Textbooks/00-姜礼尚 && xelatex main.tex
```

# Install

## Step1

```bash
Null
```

## License

This repository is for personal academic note-taking and course study purposes only.

The lecture notes, exercises, figures, and derivative materials are organized for learning and review. Original textbook content belongs to its respective authors and publishers. Please do not use this repository for commercial distribution.

Unless otherwise stated, original notes written by the repository owner are shared for non-commercial educational reference.

## Acknowledgements

This repository references the textbook structure of Jiang Lishang's *Partial Differential Equations* for personal study organization. All rights to the original textbook content remain with the original author and publisher.

## Contributors

- [No8ah](https://github.com/No8ah) — repository maintainer, notes organization, LaTeX structure, figures, and course material curation.
