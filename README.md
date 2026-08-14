# PartialDifferentialEquations

偏微分方程（PDE）课程笔记与习题集。Course notes, exercises and figures for Partial Differential Equations.

## Course Architecture

<p align="center">
  <img src="pde_course_architecture.drawio.svg" width="100%" alt="PDE Course Architecture" />
</p>

## Structure

```
PartialDifferentialEquations/
├── main.tex
├── 01-Content/        # 章节笔记（3 章 × 节 × 小节）
│   ├── chapter01-Introduction/
│   ├── chapter02-FirstOrderPDE/
│   └── chapter03-SecondOrderPDE/
├── 02-Exercises/      # 习题（镜像笔记结构）
├── 03-Figures/        # 章节配图
├── 04-References/     # references.bib
└── Settings/          # PackageSet/EnvironmentSet/CommandSet/TheoremSet
```

## Chapters

| Chapter | 内容 |
|---------|------|
| 01-Introduction | 基本概念、分类、典型例子（Laplace/Heat/Wave） |
| 02-FirstOrderPDE | 特征线法、输运方程、Hamilton-Jacobi 方程 |
| 03-SecondOrderPDE | 分类（椭圆/抛物/双曲）、Laplace、Heat、Wave 方程 |

## Build

```bash
xelatex main.tex
```

See [CONTRIBUTING.md](CONTRIBUTING.md).
