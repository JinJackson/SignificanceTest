# 显著性检验（Significance Test）

显著性检验（Significance Test）主要分为两个类别：

+ **Statistical Significance Test (统计显著性检验)**

  计量方式：p-value < 0.05

  目的：检验原始分布与目标分布之间是否具有显著差异性

+ **Practical Significance Test (现实显著性检验)**

  计量方式：effect size（cohen's d）（统计效应）

  目的：检验原始分布与目标分布之间的差异性有多大

“[NLPStatTest: A Toolkit for Comparing NLP System Performance](https://arxiv.org/abs/2011.13231)”中提出在NLP领域除了Statistical Significance，做Practical Significance也是有必要的

> 2.2.3 Effect Size Estimation
>
>  In most experimental NLP papers employing significance testing, the p-value is the only quantity reported. However, the p-value is often misused and misinterpreted. For instance, statistical significance is easily conflated with practical significance; as a result, NLP researchers often run significance tests to show that the performances of two NLP systems are different (i.e., statistical significance), without measuring the degree or the importance of such a difference (i.e., practical significance).



**使用说明：**

Statistical Significance Test (统计显著性检验)：

```python
python Statistical_significance.py file1 file2 0.05
```



Practical Significance Test (现实显著性检验):

```
python Practical_significance.py file1 file2
```

