---
title: "Measures of Variability"
linktitle: "Week 4: Measures of Variability"
menu:
  tasks:
    parent: Homeworks
    weight: 4
type: docs
weight: 2
editor_options: 
  chunk_output_type: console
---
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />
<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>
<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />



<style>
span.boxed {
  border: 0px solid #FFFFFF;
  padding: 5px;
  color: #FFFFFF;
  background-color: #005b96;
  display: inline;
} 

table {
   margin-left: auto;
   margin-right: auto;
}

table thead th { border-bottom: 1px solid #ddd; 
}

th, td { padding: 5px; 
}

tr:nth-child(even) { background: #ffffff; 
}
</style>

### Homework


<center>
<table>
 <thead>
  <tr>
   <th style="text-align:center;"> Chapter </th>
   <th style="text-align:left;"> Problems </th>
   <th style="text-align:left;"> Source </th>
   <th style="text-align:left;"> Pages </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:center;font-weight: bold;"> 4 </td>
   <td style="text-align:left;"> 1, 2, 3, 7, 8, 11, 12, 13 </td>
   <td style="text-align:left;"> Social Statistics for a Diverse Society </td>
   <td style="text-align:left;"> 143-150 </td>
  </tr>
</tbody>
</table>
</center>

Notes: 

- Please submit this at the beginning of class next week.
- Remember to follow the [homework guidelines](/tasks/#homeworks) for consideration.

<!--
to the Submission Portal on [ecampus](https://ecampus.wvu.edu/){target="_blank"} by 11:59 PM next Wednesday.<br>
-->

#### Solutions

*Posted after class day and time next week.*

<!--
<details><summary>1</summary>
<p>

a. There are <span class="boxed">seven</span> response categories for political views.

b. We can calculate the percentage square by
<center>
<table class="table table-striped table-hover table-condensed" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Political Views </th>
   <th style="text-align:center;"> Percentage `\(c\)` </th>
   <th style="text-align:center;"> Percentage Squared `\(c^2\)` </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Extremely liberal </td>
   <td style="text-align:center;"> 5.5 </td>
   <td style="text-align:center;"> 30.25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Liberal </td>
   <td style="text-align:center;"> 12.0 </td>
   <td style="text-align:center;"> 144.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Slightly liberal </td>
   <td style="text-align:center;"> 12.3 </td>
   <td style="text-align:center;"> 151.29 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Moderate </td>
   <td style="text-align:center;"> 37.8 </td>
   <td style="text-align:center;"> 1428.84 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Slightly conservative </td>
   <td style="text-align:center;"> 13.2 </td>
   <td style="text-align:center;"> 174.24 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Conservative </td>
   <td style="text-align:center;"> 15.0 </td>
   <td style="text-align:center;"> 225.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Extremely conservative </td>
   <td style="text-align:center;"> 4.2 </td>
   <td style="text-align:center;"> 17.64 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;color: white !important;background-color: #559e83 !important;"> Total </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 100.0 </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 2171.26 </td>
  </tr>
</tbody>
</table>
</center>
yields <span class="boxed">$\sum c^2 =  2171.26$</span>.

c. We can calculate the IQV by
`\begin{aligned}
IQV&= \dfrac{7\cdot(100^2-2171.26)}{100^2\cdot (7-1)}\\\\
&= \dfrac{54801.18}{60000}\\\\
&\approx 0.91
\end{aligned}`
which is relatively close to 1 suggesting that <span class="boxed">Americans are fairly diverse in their political views</span>.
</p>
</details>

<details><summary>2</summary>
<p>

a. For the female population where `\(N = 629\)`, we have 
<center>
`\(Q_1 = 629\cdot 0.25 = 157.25\)` 
</center>
<center>
`\(Q_3 = 629 \cdot 0.75 = 471.75\)`
</center>
or about the 158th and 472nd cases which are representative of cases where the degree are in the High school graduate and Bachelor's degree categories, respectively. This yields `\(IQR = 471.75-157.25=314.5\)` which includes those who have a highest attained degree of <span class="boxed">high school, junior college and bachelor's </span>.<br><br>
For the male population where `\(N = 488\)`, we have 
<center>
`\(Q_1 = 488 \cdot 0.25 = 122\)`
</center>
<center>
`\(Q_3 = 488 \cdot 0.75 = 366\)`
</center>
or the 122nd and 366th cases which are representative of cases where the degree are in the High school graduate and Bachelor's degree categories, respectively. This yields `\(IQR = 366-122=244\)` that includes those who have a highest attained degree of <span class="boxed">high school, junior college and bachelor's </span>.<br><br> 
So <span class="boxed">both IQRs provide the same groups of cases</span>.

b. Based on the IQR calculation, we know that 50% of all cases for males and females lies between high school and bachelor’s degree, <span class="boxed">but that does not inform us about the variability of the distribution</span>. A better measure would be IQV and if interval-ratio measures were available, the variance and standard deviation would provide better information and estimates. 

</p>
</details>

<details><summary>3</summary>
<p>

a. The range of convictions in 

- 2010 is given by `\(397 – 108 =\)` <span class="boxed">$289$</span>.
- 2015 is given by `\(402 – 97 =\)` <span class="boxed">$305$</span>.
Therefore the range of conviction in <span class="boxed">2015 is larger</span>.

b. The mean number in **2010** across all levels of government was
`\begin{aligned}
\overline{Y} &= \dfrac{397+108+280}{3}\\\\
&\approx 261.67
\end{aligned}`
or about an average of <span class="boxed">262 convictions</span>.<br><br> The mean number in **2015** across all levels of government was
`\begin{aligned}
\overline{Y} &= \dfrac{402+97+200}{3}\\\\
&= 233
\end{aligned}`
or an average of <span class="boxed">233 convictions</span>.

c. The sum of squares can be found by
<center>
<table class="table table-striped table-hover table-condensed" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Government Level </th>
   <th style="text-align:center;"> Number of Convictions </th>
   <th style="text-align:center;"> `\(Y-\overline{Y}\)` </th>
   <th style="text-align:center;"> `\((Y-\overline{Y})^2\)` </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Federal </td>
   <td style="text-align:center;"> 397 </td>
   <td style="text-align:center;"> `\(397 - 261.1 = 135.33\)` </td>
   <td style="text-align:center;"> `\((135.33)^2 = 18314.21\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;"> State </td>
   <td style="text-align:center;"> 108 </td>
   <td style="text-align:center;"> `\(108 - 261.67 = -153.67\)` </td>
   <td style="text-align:center;"> `\((-153.67)^2 = 23614.47\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Local </td>
   <td style="text-align:center;"> 280 </td>
   <td style="text-align:center;"> `\(280 - 261.67 = 18.33\)` </td>
   <td style="text-align:center;"> `\((18.33)^2 = 335.99\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;color: white !important;background-color: #559e83 !important;"> Total </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 785 </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> $ $ </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 42264.67 </td>
  </tr>
</tbody>
</table>
</center>
implying that 
`\begin{aligned}
S &= \sqrt{\dfrac{42264.67}{2}}\\\\
&\approx 145.37
\end{aligned}`
So in **2010**, there was a standard deviation of about <span class="boxed">145.37</span>.<br><br>
The sum of squares can be found by
<center>
<table class="table table-striped table-hover table-condensed" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Government Level </th>
   <th style="text-align:center;"> Number of Convictions </th>
   <th style="text-align:center;"> `\(Y-\overline{Y}\)` </th>
   <th style="text-align:center;"> `\((Y-\overline{Y})^2\)` </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Federal </td>
   <td style="text-align:center;"> 402 </td>
   <td style="text-align:center;"> `\(402 - 233 = 169\)` </td>
   <td style="text-align:center;"> `\((169)^2 = 28561\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;"> State </td>
   <td style="text-align:center;"> 97 </td>
   <td style="text-align:center;"> `\(97 - 233 = -136\)` </td>
   <td style="text-align:center;"> `\((-136)^2 = 18496\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Local </td>
   <td style="text-align:center;"> 200 </td>
   <td style="text-align:center;"> `\(200 - 233 = -33\)` </td>
   <td style="text-align:center;"> `\((-33)^2 = 1089\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;color: white !important;background-color: #559e83 !important;"> Total </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 699 </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> $ $ </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 48146 </td>
  </tr>
</tbody>
</table>
</center>
implying that 
`\begin{aligned}
S &= \sqrt{\dfrac{48146}{2}}\\\\
&\approx 155.15
\end{aligned}`
So in **2015**, there was a standard deviation of about <span class="boxed">155.15</span>.

d. The standard deviation is larger in the latter time period so <span class="boxed">there is more variability in number of convictions in 2015 than in 2010</span>. This <span class="boxed">supports the results of the range</span>.

</p>
</details>

<details><summary>7</summary>
<p>

a. The range can be found by `\(4.50-2.20=\)` <span class="boxed">$2.30$</span>.<br><br>
Meanwhile for `\(n=10\)`, we have
<center>
25th percentile: `\(10\cdot 0.25 = 2.5\)`th case so `\(\dfrac{2.40+2.50}{2}=2.45\)`
</center>
<center>
75th percentile: `\(10\cdot 0.75 = 7.5\)`th case so `\(\dfrac{3.60+3.60}{2}=3.60\)`
</center>
S. the IQR is `\(3.60 – 2.45 =\)` <span class="boxed">$1.15$</span>. While both measures will work, the <span class="boxed">range is a bit more precise</span>, in that <span class="boxed">it provides a better picture of the variability of divorce rates for all states in the sample</span>.

b. The sum of squares can be found by
<center>
<table class="table table-striped table-hover table-condensed" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> State </th>
   <th style="text-align:center;"> Divorce rate/thousand </th>
   <th style="text-align:center;"> `\(Y-\overline{Y}\)` </th>
   <th style="text-align:center;"> `\((Y-\overline{Y})^2\)` </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Florida </td>
   <td style="text-align:center;"> 3.6 </td>
   <td style="text-align:center;"> 3.5 – 3.14 </td>
   <td style="text-align:center;"> 0.210 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Idaho </td>
   <td style="text-align:center;"> 3.9 </td>
   <td style="text-align:center;"> 3.9 – 3.14 </td>
   <td style="text-align:center;"> 0.460 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Maine </td>
   <td style="text-align:center;"> 3.2 </td>
   <td style="text-align:center;"> 3.2 – 3.14 </td>
   <td style="text-align:center;"> 0.004 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Maryland </td>
   <td style="text-align:center;"> 2.5 </td>
   <td style="text-align:center;"> 2.5 – 3.14 </td>
   <td style="text-align:center;"> 0.410 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Nevada </td>
   <td style="text-align:center;"> 4.5 </td>
   <td style="text-align:center;"> 4.5 – 3.14 </td>
   <td style="text-align:center;"> 1.850 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> New Jersey </td>
   <td style="text-align:center;"> 2.6 </td>
   <td style="text-align:center;"> 2.6 – 3.14 </td>
   <td style="text-align:center;"> 0.290 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Texas </td>
   <td style="text-align:center;"> 2.2 </td>
   <td style="text-align:center;"> 2.2 – 3.14 </td>
   <td style="text-align:center;"> 0.880 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Vermont </td>
   <td style="text-align:center;"> 2.9 </td>
   <td style="text-align:center;"> 2.9 – 3.14 </td>
   <td style="text-align:center;"> 0.058 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Wisconsin </td>
   <td style="text-align:center;"> 2.4 </td>
   <td style="text-align:center;"> 2.4 – 3.14 </td>
   <td style="text-align:center;"> 0.550 </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;color: white !important;background-color: #559e83 !important;"> Total </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 31.4 </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;">  </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 4.922 </td>
  </tr>
</tbody>
</table>
</center>
implying that 
`\begin{aligned}
\overline{Y} &= \sqrt{\dfrac{3.6 + 3.6 + 3.9 + 3.2 + 2.5 + 4.5 + 2.6 + 2.2 + 2.9 + 2.4}{10}}\\\\
&\approx 3.14
\end{aligned}`
and
`\begin{aligned}
S &= \sqrt{\dfrac{4.922}{9}}\\\\
&\approx 0.74
\end{aligned}`
So between **1997-2017**, the average divorce rate per 1000 people was about `\(3\)` with an approximated standard deviation of <span class="boxed">0.74</span>.

c. Divorce rates may vary by state due to multiple factors which are not represented in the included data set such as variations in <span class="boxed">employment status</span>, <span class="boxed">policies and laws by region (i.e. states with no-fault divorce laws)</span>, <span class="boxed">religious beliefs</span>, etc.

</p>
</details>

<details><summary>8</summary>
<p>

a. `DEGREE` is an <span class="boxed">ordinal measure</span> whereas `AGEKDBRN` is an <span class="boxed">interval measure</span>.

b. As `DEGREE` increases, `AGEKDBRN` increases as well implying the likelihood of a positive relationship. The youngest first-time parents are those with less than a high school degree, while the oldest first-time parents are those with graduate degrees with difference  `\(28.59 – 21.33 = 7.26\)` years. The variability in age when first child was born is larger as educational attainment increases. The standard deviation for the high school degree group is largest at `\(5.498\)` years, the smallest is for the some college group with `\(4.581\)`. 

</p>
</details>

<details><summary>11</summary>
<p>

a. `Type of Work` is a nominal variable implying that the appropriate measure of variability as the <span class="boxed">index of qualitative variation (IQV)</span>.

b. The pertage squared for both grades can be found by
<table class="table table-striped table-hover table-condensed" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Type of Work </th>
   <th style="text-align:center;"> Grade 8 Percentage `\(c\)` </th>
   <th style="text-align:center;"> Grade 8 Percentage Squared `\(c^2\)` </th>
   <th style="text-align:center;"> Grade 10 Percentage `\(c\)` </th>
   <th style="text-align:center;"> Grade 10 Percentage Squared `\(c^2\)` </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Lawn work </td>
   <td style="text-align:center;"> 28 </td>
   <td style="text-align:center;"> `\((28)^2 = 784\)` </td>
   <td style="text-align:center;"> 20 </td>
   <td style="text-align:center;"> `\((20)^2 = 400\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Food service </td>
   <td style="text-align:center;"> 3 </td>
   <td style="text-align:center;"> `\((3)^2 = 9\)` </td>
   <td style="text-align:center;"> 10 </td>
   <td style="text-align:center;"> `\((10)^2 = 100\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Babysitting </td>
   <td style="text-align:center;"> 37 </td>
   <td style="text-align:center;"> `\((37)^2 = 1369\)` </td>
   <td style="text-align:center;"> 28 </td>
   <td style="text-align:center;"> `\((28)^2 = 784\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;font-weight: bold;color: white !important;background-color: #559e83 !important;"> Other </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 32 </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> `\((32)^2 = 1024\)` </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> 42 </td>
   <td style="text-align:center;font-weight: bold;color: white !important;background-color: #559e83 !important;"> `\((42)^2 = 1764\)` </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Total </td>
   <td style="text-align:center;"> 100 </td>
   <td style="text-align:center;"> `\(3186\)` </td>
   <td style="text-align:center;"> 100 </td>
   <td style="text-align:center;"> `\(2048\)` </td>
  </tr>
</tbody>
</table>
So the IQV for both grades can be found by
<center>
Grade 8: `\(\dfrac{4\cdot(100^2-3186)}{100^2\cdot (4-1)} = \dfrac{27256}{30000} = 0.91\)`
</center>
<center>
Grade 10: `\(\dfrac{4\cdot(100^2-3048)}{100^2\cdot (4-1)} = \dfrac{27808}{30000} = 0.93\)`
</center>
implying <span class="boxed">IQV(Grade 8) `\(=0.91\)`</span> and <span class="boxed">IQV(Grade 10) `\(=0.93\)`</span>.

c. Though both IQVs are greater than `\(0.90\)`, there is <span class="boxed">slightly more variation among 10th graders than 8th graders<span class="boxed"> in the type of jobs they hold. The difference may be attributed to <span class="boxed">more employment options for older students</span> and <span class="boxed">limitations for younger students</span>xxxx leading to more informal jobs such as lawn work and babysitting. 

</p>
</details>


<details><summary>12</summary>
<p>

Using the summary statistics for life expectancy
<center>
<table class="table table-striped table-hover table-condensed" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Measure </th>
   <th style="text-align:center;"> Statistic for European Countries </th>
   <th style="text-align:center;"> Statistic for Non-european Countries </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Median </td>
   <td style="text-align:center;"> 81.500 </td>
   <td style="text-align:center;"> 82.70 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Variance </td>
   <td style="text-align:center;"> 7.985 </td>
   <td style="text-align:center;"> 11.65 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Standard deviation </td>
   <td style="text-align:center;"> 2.830 </td>
   <td style="text-align:center;"> 3.41 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Minimum </td>
   <td style="text-align:center;"> 75.300 </td>
   <td style="text-align:center;"> 76.30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Maximum </td>
   <td style="text-align:center;"> 82.000 </td>
   <td style="text-align:center;"> 85.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Range </td>
   <td style="text-align:center;"> 6.700 </td>
   <td style="text-align:center;"> 9.20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Interquartile range </td>
   <td style="text-align:center;"> 3.800 </td>
   <td style="text-align:center;"> 4.95 </td>
  </tr>
</tbody>
</table>
</center>
we find that the variable is interval ratio implying that variance (or standard deviation), range, or IQR are possible and valid. Among these three measures, variance and/or standard deviation is preferred for precision. For just the average life expectancy for these 10 countries, we should rely on the mean.<br><br>
On average, non-European countries have a slightly higher life expectancy at birth ($82.00$ vs. `\(80.30\)`). Both the mean and median are higher for non-European countries than for European countries. Also, the distribution of non-European countries exhibits more variability; the standard deviation for European countries is `\(3.41\)` years, while for non-European countries it is `\(2.83\)` years.<br><br>
These differences might be explained by access and availability of health care and/or diet. However, the difference might simply be random due to the small number of countries presented in this example. We are likely to find different results if more countries were incorporated into the analyses.

</p>
</details>

<details><summary>13</summary>
<p>

Overall, <span class="boxed">Clinton voters were younger</span>, <span class="boxed">more educated</span>, and <span class="boxed">attended religious services less</span> than Trump voters. The youngest voters were male Clinton voters at `\(50.49\)` years ($s = 18.84$), followed by female Clinton voters, `\(51.93\)` years ($s = 18.21$). For education, males who voted for Clinton had the highest mean of `\(14.69\)` ($s = 2.73$). Males who voted for Trump had `\(13.80\)` years of education ($s = 2.75$). Trump voters, both males and females, attended religious services more often than Clinton voters. Mean scores were `\(3.72\)` for males ($s = 2.93$) and `\(3.82\)` for females ($s = 2.75$), indicating church attendance about several times a year to once a month. The standard deviations indicate a consistency in the distributions of education, age, and religious service attendance across all four groups. The largest standard deviations are for age, ranging from `\(15.94\)` to `\(18.84\)` years. These wide standard deviations indicate more dispersion around the mean age scores. 

</p>
</details>
-->
