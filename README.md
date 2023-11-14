# A-B-Testing-Case-study Analysis

This repository contains a comprehensive analysis of the Vungle A/B testing case study. Utilizing the MD5 hashing algorithm, we explore the effectiveness of two different ad-serving algorithms, A and B, in the context of mobile advertising. The analysis is centered on various metrics such as eRPM (effective revenue per 1,000 impressions), conversion rates, and overall performance efficiency.

Key Components:
<b>User Assignment</b>: We examine how users were distributed between Algorithms A and B, with a focus on the 15/16 to 1/16 proportion established via MD5 hashing.<br>
<br>
<b>Effectiveness Metrics</b>: The primary metric used for assessing the campaign's success is eRPM, offering insights into the revenue generation capabilities of each algorithm.<br>
<br>
<b>Algorithm Comparison</b>: Through statistical tests like the 2-sample and paired t-tests, we compare the mean eRPMs of both algorithms to determine the superior performer.<br>
<br>
<b>Conversion Rates</b>: We calculate and compare the conversion rates for each algorithm, providing a clear view of their effectiveness in user engagement.<br>
<br>
<b>Statistical Significance</b>: Utilizing a proportions test, we assess which algorithm demonstrates statistically significant better performance based on conversion rates.<br>
<br>
<b>Cost-Benefit Analysis</b>: We calculate the minimum expected lift from Algorithm B using the lower bound of the confidence interval obtained from the paired t-test (Confidence Interval: [0.04173767, 0.17959566]).<br>
<br>
<b>Minimum Lift Calculation</b>: By applying the lower bound of the confidence interval to the total impressions processed by Algorithm B, we estimate the minimum additional income that could be generated.<br>
<br>
<b>Decision Making</b>: Our analysis shows that the minimum lift from Algorithm B exceeds $10,500, which is significantly higher than the additional cost of $2,000 for its operation.<br>
<br>
<b>Conclusion</b>:
Based on our financial analysis, Algorithm B should be favored over Algorithm A. The substantial additional revenue of over $8,500 per month, after accounting for the extra costs, strongly supports the decision to implement Algorithm B for enhanced profitability and efficiency in Vungle's ad-serving operations.
