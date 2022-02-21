Dataset1 (chained callback and eCDF usage)
==========================================

This plot is of the 2014 US States population and it allows users to see which state takes up the most relative population for each US region. This utilizes the plotly eCDF plot and uses chained callbacks to allow users to select one of 7 US regions and then select relative states inside of it.

I find this visualization interesting because it shows the population distribution for each US region. For example, I didn't realize that nearly half the people in the rocky mountain region lived in Colorado.

**eCDF vs. Histogram**
One of the reasons why an eCDF plot is preferable to a histogram is that it is easier to determine key values such as the minimum, maximum, and percentiles from the diagram. A histogram displays counts in bins/intervals, so one cannot determine any of this exact key values from a histogram. Also, outliers in histograms tend to stretch out the distribution so the original distribution (distribution without the outlier) becomes hard to recognize. Removing the outlier is not good too and there is no way to show the data while easily showing that the outlier was removed from the data. However, in an eCDF plot, if we were to remove outliers, it would be obvious because the graph would not reach y=1. Essentially, rescaling the x-axis and dealing with outliers is easier with an eCDF plot vs. histograms.

Source: https://www.andata.at/en/software-blog-reader/why-we-love-the-cdf-and-do-not-like-histograms-that-much.html

