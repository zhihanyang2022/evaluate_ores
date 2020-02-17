# Evaluating ORES

Disclaimer: this is an exploratory project because I operationalized "article credibility" as simply the number of external links; this assumption requires further research.

ORES stands for Objective Revision Evaluation Service; it is a machine-learning-based article-quality classifier for Wikipedia.

## Motivation

Having a clear sense of how less interpretable quality-control tools are performing is crucial because Wikipedia articles are applied to high stake decision-making scenarios such as diagnosis of illnesses.

## Hypothesis

As we can see in the table below, Wikipedia rates the quality of an article by the following categories: FA, FL, A, GA, B, C, Start and Stub (from the best to the worst). It should be noted that quality categories FL (between FA and GA) and A (between GA and B) are not assigned to any articles. 

<img src="https://github.com/zhihanyang2022/evaluate_ores/blob/master/ores_ratings.png" alt="drawing" width="500"/>

The <u>hypothesis</u> was that number of external links (the measure of "article credibility" used in this project) increases as quality classification (made by the ORES classifier) improves.

## Data Collection

The number of external links and the total number of pageviews (over 60 days, from March 23rd 2019 to May 22nd 2019) were collected for 10367 articles under the category Medicine.

## Results

We can see that the increment in article credibility is very small from quality classification to B to GA.

<img src="https://github.com/zhihanyang2022/evaluate_ores/blob/master/external_links_vs_quality_ratings.png" alt="drawing" width="500"/>

## Conclusion

Because the increment in article credibility is very small from quality classification to B to GA, we might need to doubt the accuracy of the ORES classifier.
