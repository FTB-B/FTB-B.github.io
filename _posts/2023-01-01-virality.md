---
title: "How to calculate Virality"
category: posts
excerpt: "Virality"
---

## <a id="introduction">1. Introduction</a>

### z-score
    A Z-score measures how many standard deviations an element is from the mean. It is used to identify how unusual a data point is. A Z-score of 0 indicates that the data point is perfectly average, a positive Z-score indicates a value higher than the mean, and a negative Z-score indicates a value lower than the mean. By comparing the Z-scores of different data points, you can understand which data points are unusually high or low.

In your case, if you want to identify domains that suddenly become popular (i.e., their share count increases significantly), calculating the Z-score could be a good approach. A high Z-score for a domain on a particular day would indicate that the domain's share count was unusually high on that day. This could potentially be an indicator of a domain going viral.

On the other hand, if you want to understand the trend in a domain's popularity over time (i.e., whether it's generally increasing or decreasing), the moving average would be more appropriate. The moving average would smooth out daily fluctuations and highlight the overall trend.

It's also possible to combine these two methods. For example, you could calculate a moving average of the Z-scores to identify trends in how unusual a domain's share count is. This could potentially identify domains that regularly have unusual spikes in popularity.

### Moving Average (Rolling Mean)
  A moving average is used to smooth out short-term fluctuations and highlight longer-term trends or cycles. When we calculate the moving average of a time series, we calculate the average of the data points within a certain window that moves over time. It's useful for identifying trends and patterns and smoothing out noise in the data.
However, it does not necessarily provide a measure of how unusual or significant a particular observation is in the context of the data.
