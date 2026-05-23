# 🌸 Iris Data Analysis and Statistical Inference  
# 鸢尾花数据分析与统计推断

---

## 项目概览 / Project Overview

本项目基于经典 Iris 鸢尾花数据集，通过探索性数据分析（EDA）、数据可视化以及统计假设检验，研究不同种类鸢尾花在萼片与花瓣特征上的差异。
通过本项目，练习使用 Python 进行数据读取、数据探索以及统计分析，并进一步理解统计推断与假设检验在数据分析中的应用。

---

## 数据概览 / Data Overview

- **样本数量**：100 条鸢尾花样本数据
- **数据来源**：Iris.csv
- **鸢尾花种类**：两种鸢尾花（各 50 个样本）
- **分析目标：**
  - 分析不同鸢尾花种类之间的属性差异
  - 探索萼片与花瓣特征分布规律
  - 通过统计检验判断不同属性均值 (萼片长度、萼片宽度、花瓣长度、花瓣宽度) 是否存在显著性差异

---

## 数据字段说明 / Data Description

| 字段名 | 含义 |
|------|------|
| Id | 样本 ID |
| SepalLengthCm | 萼片长度（cm） |
| SepalWidthCm | 萼片宽度（cm） |
| PetalLengthCm | 花瓣长度（cm） |
| PetalWidthCm | 花瓣宽度（cm） |
| Species | 鸢尾花种类 |

---

## 分析流程 / Analysis Process

本项目主要围绕鸢尾花数据的探索性分析与统计推断展开，流程包括：

1. **数据读取与基础检查**

2. **数据清洗**

3. **可视化探索数据**
   - 初步观察不同种类鸢尾花属性分布

5. **统计假设检验**
   - 分种类整理表格数据
   - 构建原假设与备择假设
   - 假设检验不同种类鸢尾花属性均值是否存在显著差异(附属性复合直方图展示)
   - 分析统计结果（p值）并进行推断

---

## 可视化内容 / Visualization Analysis

- **不同种类鸢尾花属性分布图**

---

## 假设检验 / Hypothesis Testing
通过统计检验方法，对不同鸢尾花在萼片与花瓣特征上的差异进行统计推断。

**原假设（H0）**
不同种类鸢尾花在属性均值上不存在显著性差异。

**备择假设（H1）**
不同种类鸢尾花在属性均值上存在显著性差异。


---

## 分析结论 / Key Findings

- **不同种类鸢尾花在花瓣长度与宽度上均存在明显差异**
- **花瓣长度特征对区分不同鸢尾花种类具有较强作用**

---

## 技术栈 / Tech Stack

- **语言**: Python
- **数据处理库**: Pandas, NumPy
- **数据可视化库**: Matplotlib, Seaborn
- **统计分析库**: SciPy
- **工具**: Jupyter Notebook, VSCode, Git & GitHub

---

## 项目结构 / Project Structure

```text
Iris-Data-Analysis/
│
├── Iris.csv
├── iris_analysis.ipynb
├── README.md
├── requirements.txt
│
└── images/
    ├── pairplot.png

```

---

## 复现指南 / Reproduction Guide

### 1. 克隆仓库

```bash
git clone https://github.com/Mochellna/Python-data-analysis-practice.git
```

### 2. 安装依赖

```bash
pip install -r requirements.txt
```

### 3. 打开 Notebook

在 Jupyter Notebook 中打开：

```text
iris_analysis.ipynb
```

### 4. 运行项目

按顺序运行 Notebook 单元格，即可复现完整的数据分析与可视化流程。
