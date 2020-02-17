# Evaluating ORES: A machine-learning-based article-quality classifier for Wikipedia

## Motivation

Moderation on Wikipedia encompasses two categories of tasks and different algorithmic tools has been developed for each of the two categories. One category of tools can be thought of as “bounty hunters”. They detect the presence of specific words that hint at potential vandalisms. The metrics used by these tools are explicitly defined by the lists of unwanted words given by human administrators. Their performances can evaluated in a straightforward manner by, for example, monitoring the rate at which vandalisms are spotted by non-administrators and the average time elapsed between a vandalistic contribution and its reversion.

Another category of tools can be best regarded as “intelligent assistants” for human administrators. They are machine-learning-based tools capable of learning decision metrics from human-labelled data and are deployed to perform cognitively demanding tasks, such as evaluating the quality of articles. These tools rely on more sophisticated and less interpretable methods, and can be much less accurate when processing data that are very different from training data. A 2009 study of physicians showed that Wikipedia is used in 26% of patient cases and by 70% of physicians for clinical purposes (Hughes et al, 2009). Therefore, *having a clear sense of how these less interpretable tools are performing is crucial because articles are applied to high stake decision-making scenarios such as diagnosis of illnesses.*

## Hypothesis

The hypothesis was that number of external links (the measure of article credibility in this project) increases as quality classification (both human's and algorithm's)improves, because both metrics are intended to measure the same underlying factor, that is, quality of articles.

## Data Collection

