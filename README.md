# Python 数据分析作品集
## 项目简介
本仓库为跨行转行数据分析学习项目，包含天文数据分析、NASA API爬虫与文本可视化两大实战项目，全程使用 Python 进行数据处理、可视化及机器学习建模。

## 项目目录
### 1. sdss_astronomy_classification
SDSS 天文星系数据挖掘项目
- 数据清洗：异常值替换、缺失值删除
- 构造天文颜色指数特征
- Seaborn 多特征可视化分析
- 逻辑回归建模对比：有无红移特征对分类效果的影响
- 技术栈：Pandas、Matplotlib、Seaborn、Scikit-learn

### 2. nasa_apod_crawler_wordcloud
NASA APOD 每日天文图片爬虫项目
- 调用 NASA 官方开放 API 爬取近30天天文图文数据
- 循环请求接口、解析 JSON 结构化存储
- 筛选图片类型数据，生成说明文本词云
- 批量展示天文图片，支持指定单日数据查询
- 敏感 API_KEY 使用占位符处理，保护隐私
- 技术栈：Requests、Pandas、WordCloud、Jupyter Notebook

## 运行说明
1. 所有项目使用 Jupyter Notebook 编写，保留完整运行结果与图表
2. NASA 项目需自行申请 NASA API_KEY 替换代码中 YOUR_API_KEY 即可运行
3. 代码均配有详细中文注释，适合初学者学习参考
