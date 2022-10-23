---
title: "Estimation"
linktitle: "Week 8: Estimation"
toc: true
output:
  rmarkdown::html_document:
    toc: true
menu:
  tasks:
    parent: Homeworks
    weight: 8
type: docs
weight: 2
editor_options: 
  chunk_output_type: console
---

<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>

<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />

{{% aes-header %}}

### Homework

<center>
<table>
<thead>
<tr>
<th style="text-align:center;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Chapter
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Problems
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Source
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Pages
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center;font-weight: bold;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
7
</td>
<td style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
1, 2, 3, 4, 5, 10
</td>
<td style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Social Statistics for a Diverse Society
</td>
<td style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
275-280
</td>
</tr>
</tbody>
</table>
</center>

Notes:

-   Please submit this at the beginning of class next week.
-   Remember to follow the [homework guidelines](/tasks/#homeworks) for consideration.

<!--
to the Submission Portal on [ecampus](https://ecampus.wvu.edu/){target="_blank"} by 11:59 PM next Wednesday.<br>
-->

### Solutions

*Posted after class day and time next week.*

<!--


<details><summary>1</summary>
<p>
a. The estimate at the 90% confidence level is 20.87–21.13%. This means that there are 90 chances out of 100 that the confidence interval will contain the true population percentage of victims in the American population. Due to the large sample size, we converted the proportions to percentages, subtracting from 100, rather than 1.
\begin{align}
s_p &= \sqrt{\dfrac{21\cdot(100-21)}{239541}}\\
&\approx 0.08
\end{align}
and
\begin{align}
CI &= 21\pm 1.65\cdot0.08\\
&= 21\pm 0.13\\
&= (20.87, 21.13)
\end{align}
So the standard error of the mean is approximately <span class="boxed">0.08</span> with a confidence interval between <span class="boxed">20.87 to 21.13</span>.

b. The true percentage of crime victims in the American population is somewhere between 20.79% and 21.21% based on the 99% confidence interval. There are 99 chances out of 100 that the confidence interval will contain the true population percentage of crime victims. 
\begin{align}
CI &= 21\pm 2.58\cdot0.08\\
&= 21\pm 0.21\\
&= (20.79, 21.21)
\end{align}
So we have a confidence interval between <span class="boxed">20.79 to 21.21</span>.
</p>
</details>

<details><summary>2</summary>
<p>
a. For lower-class respondents, we have
\begin{align}
S_{\overline{Y}} &=\dfrac{3.08}{\sqrt{102}}\\[0.5ex]
&\approx 0.30
\end{align}
and
\begin{align}
CI &= 12.19\pm 1.96\cdot0.30\\
&= 12.19\pm 0.59\\
&= (11.60, 12.78)
\end{align}
So the estimated standard error for the sampling distribution is approximately <span class="boxed">0.30</span> with a confidence interval between <span class="boxed">11.60 to 12.78</span>.<br><br>
For working-class respondents, we have
\begin{align}
S_{\overline{Y}} &=\dfrac{2.93}{\sqrt{523}}\\[0.5ex]
&\approx 0.13
\end{align}
and
\begin{align}
CI &= 13.16\pm 1.96\cdot0.13\\
&= 13.16\pm 0.25\\
&= (12.91, 13.41)
\end{align}
So the estimated standard error for the sampling distribution is approximately <span class="boxed">0.13</span> with a confidence interval between <span class="boxed">12.91 to 13.41</span>.

b. For lower-class respondents, we have
\begin{align}
CI &= 12.19\pm 2.58\cdot0.30\\
&= 12.19\pm 0.77\\
&= (11.42, 12.96)
\end{align}
So the confidence interval is between <span class="boxed">11.42 to 12.96</span>.<br><br>
For working-class respondents, we have
\begin{align}
CI &= 14.60\pm 2.58\cdot0.13\\
&= 14.60\pm 0.34\\
&= (14.26, 14.94)
\end{align}
So the confidence interval is between <span class="boxed">14.26 to 14.94</span>.

c. As our confidence level increases, the confidence interval gets wider, not narrower. This is because a wider interval is needed to increase the probability that our calculated interval includes the true population value. Thus, increasing confidence leads to less precise intervals.
</p>
</details>

<details><summary>3</summary>
<p>
a. For Canadians we have
\begin{align}
s_p &= \sqrt{\dfrac{0.51\cdot(1-0.51)}{1004}}\\
&\approx 0.02
\end{align}
and
\begin{align}
CI &= 0.51\pm 1.96\cdot0.02\\
&= 0.51\pm 0.04\\
&= (0.47, 0.55)
\end{align}
So the estimated standard error of proportions is approximately <span class="boxed">0.02</span> with a confidence interval between <span class="boxed">0.47 to 0.55</span>.

b. For Americans we have \begin{align}
CI &= 0.45\pm 1.96\cdot0.02\\
&= 0.45\pm 0.04\\
&= (0.39, 0.49)
\end{align}
implying a confidence interval between <span class="boxed">0.39 to 0.49</span>.

c. Based upon the calculated 95% confidence interval, the majority of Americans do not believe climate change is a serious problem. The true percentage of Americans who believe climate change is a serious problem is under 50%, somewhere between 39% and 49%, based upon this Pew Research Center sample. On the other hand, it is possible that the majority of Canadians believe climate change is a serious problem. We can be 95% confident that the true percentage of Canadians is somewhere between 47% and 55%.
</p>
</details>

<details><summary>4</summary>
<p>
a. We have a 90% confidence interval for the males by calculating
\begin{align}
s_p &= \sqrt{\dfrac{0.21\cdot(1-0.21)}{337}}\\
&\approx 0.02
\end{align}
and
\begin{align}
CI &= 0.21\pm 1.65\cdot0.02\\
&= 0.21\pm 0.03\\
&= (0.18, 0.24)
\end{align}
implying an estimated standard error of proportions is approximately <span class="boxed">0.02</span> with a confidence interval between <span class="boxed">0.18 to 0.24</span>.

b. We have a 90% confidence interval for the demales by calculating
\begin{align}
s_p &= \sqrt{\dfrac{0.37\cdot(1-0.37)}{441}}\\
&\approx 0.02
\end{align}
and
\begin{align}
CI &= 0.37\pm 1.65\cdot0.02\\
&= 0.37\pm 0.03\\
&= (0.34, 0.40)
\end{align}
implying an estimated standard error of proportions is approximately <span class="boxed">0.02</span> with a confidence interval between <span class="boxed">0.34 to 0.40</span>.

</p>
</details>

<details><summary>5</summary>
<p>
<div style="padding-left: 30px;">
Due to the large sample size, we converted the proportion to full percentages, subtracting from 100 rather than 1.
\begin{align}
s_p &= \sqrt{\dfrac{51\cdot(100-51)}{5490}}\\
&\approx 0.67
\end{align}
and
\begin{align}
CI &= 51\pm 1.96\cdot0.67\\
&= 51\pm 0.13\\
&= (49.69, 52.31)
\end{align}
We set the interval at the 95% confidence level. However, no matter whether the 90%, 95%, or 99% confidence level is chosen, the calculated interval includes values below 50% for the vote for a Republican candidate. Therefore, you should tell your supervisors that it <span class="boxed">would not be possible to declare a Republican candidate the likely winner of the votes coming from men if there was an election today because it seems quite possible that less than a majority of male voters would support her/him.</span>
</div>
</p>
</details>

<details><summary>10</summary>
<p>
For Bernie Sanders we have
\begin{align}
s_p &= \sqrt{\dfrac{0.55\cdot(1-0.55)}{1754}}\\
&\approx 0.01
\end{align}
and
\begin{align}
CI &= 0.55\pm 1.65\cdot0.01\\
&= 0.55\pm 0.02\\
&= (0.53, 0.57)
\end{align}
implying an estimated standard error of proportions is approximately <span class="boxed">0.02</span> with a confidence interval between <span class="boxed">0.53 to 0.57</span>.<br><br>
For Hillary Clinton we have
\begin{align}
s_p &= \sqrt{\dfrac{0.38\cdot(1-0.38)}{1754}}\\
&\approx 0.01
\end{align}
and
\begin{align}
CI &= 0.38\pm 1.65\cdot0.01\\
&= 0.38\pm 0.02\\
&= (0.36, 0.40)
\end{align}
implying an estimated standard error of proportions is approximately <span class="boxed">0.02</span> with a confidence interval between <span class="boxed">0.36 to 0.40</span>.
</p>
</details>
-->
