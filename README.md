# Evaluating ORES

ORES is a machine-learning-based article-quality classifier for Wikipedia.

## Motivation

Having a clear sense of how less interpretable quality-control tools are performing is crucial because Wikipedia articles are applied to high stake decision-making scenarios such as diagnosis of illnesses.

## Hypothesis

As we can see in the table below, Wikipedia rates the quality of an article by the following categories: FA, FL, A, GA, B, C, Start and Stub (from the best to the worst). It should be noted that quality categories FL (between FA and GA) and A (between GA and B) are not assigned to any articles. 

<img src="https://github.com/zhihanyang2022/evaluate_ores/blob/master/ores_ratings.png" alt="drawing" width="500"/>



The hypothesis was that number of external links (the measure of article credibility in this project) increases as quality classification (both human's and algorithm's)improves, because both metrics are intended to measure the same underlying factor, that is, quality of articles.

## Data Collection and Results

Please read the manuscript, thanks!

