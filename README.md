# 奶牛疾病预测

## 1. 项目介绍

项目提供的数据特征是：日产量、日活动量、日反刍量、泌乳天数、泌乳期、新疾病类型。要求根据奶牛运动数据和泌乳数据、预测奶牛疾病类型。重点解决数据清洗、样本不均衡和精度提升。

## 2. 环境依赖

请下载给定数据文件：

- 反刍数据0901-0915.xlsx
- 反刍数据0916-0930.xlsx
- 泌乳数据 2021_10_9 16-41-26.xlsx
- 活动数据20210901-20210915.xlsx
- 活动数据20210916-20210930.xlsx
- 疾病记录(2021年10月09日).xlsx

要求 Python 版本：3.7~3.10，安装依赖：

```bash
pip install -r requirements.txt
```

使用 Docker 快速体验环境：

```bash
docker build -t cow-disease-prediction -f docker/Dockerfile .
docker run -it --rm cow-disease-prediction bash
```

## 3. 项目报告

请参考 [此文档](./docs/report.md)。
