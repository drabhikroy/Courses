---
title: "The Chi Square Test and Measures of Association"
linktitle: "Week 12: The Chi Square Test and Measures of Association"
toc: true
output:
  rmarkdown::html_document:
    toc: true
menu:
  tasks:
    parent: Homeworks
    weight: 12
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
10
</td>
<td style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
1, 2, 3, 5, 7, 13
</td>
<td style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Social Statistics for a Diverse Society
</td>
<td style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
364-372
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
*Note: To stay consistent with the general literature, the* `\(\chi^2\)` *value obtained will be referenced by the variable* `\(\chi^2_{obt}\)`.
<details><summary>1</summary>
<p>

a. We have 
`\begin{align}
df &= (3-1)\cdot(2-1)\\
   &= 2
\end{align}`
yielding <span class="boxed">2 degrees of freedom</span>.

b. We have `\(\chi^2 = 3.311\)`. With `\(\chi^2_{obt} =  0.191 > \alpha = 0.01\)`, <span class="boxed">we fail to reject `\(H_0\)` and conclude that sex and opinion of whether or not people can be trusted are likely independent</span>. Specifically, similar percentages of men ($34.94$%) and women ($29.7$%) felt that people can be trusted.

c. If `\(\alpha = 0.05\)`, `\(\chi^2_{obt} =  0.191\)` would still be greater and thus <span class="boxed">we would still reject `\(H_0\)`</span>.

d. We have `\(\lambda = 0.000\)` implying that there <span class="boxed">is no proportional reduction of error using sex to predict whether or not people can be trusted</span>.

</p>
</details>

<details><summary>2</summary>
<p>
a. There does not appear to be a relationship between gender and views on restoring the voting rights of felons in prison. `\(30\)`% of respondents supported restoring the voting rights of felons in prison, with only a slightly greater percentage of men ($31$%) reporting such compared to women ($28$%). 
<div align="center">
<div style="width: 50%; margin:0 left;text-align: left;">
<table class="table" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Restoring Voting Rights </th>
   <th style="text-align:center;"> Men </th>
   <th style="text-align:center;"> Women </th>
   <th style="text-align:center;"> Total </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> Support </td>
   <td style="text-align:center;"> 31% </td>
   <td style="text-align:center;"> 28% </td>
   <td style="text-align:center;"> 30% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Oppose </td>
   <td style="text-align:center;"> 69% </td>
   <td style="text-align:center;"> 71% </td>
   <td style="text-align:center;"> 70% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Total </td>
   <td style="text-align:center;"> 100% </td>
   <td style="text-align:center;"> 99% </td>
   <td style="text-align:center;"> 100% </td>
  </tr>
</tbody>
</table>
</div>
</div>

b. We <span class="boxed">fail to reject `\(H_0\)` of no relationship and conclude that there is not a relationship between gender and views on restoring the voting rights of felons in prison at the `\(0.05\)` `\(\alpha\)` level</span>. 
</p>
</details>

<details><summary>3</summary>
<p>
a. <span class="boxed">A higher percentage of White respondents ($38.14$%), compared to Black respondents ($23$%), reported that people could be trusted</span>.

b. <span class="boxed">For Black respondents, a slightly higher percentage of men ($15.1$%) compared to women ($12.5$%) reported that people could be trusted</span>.

c. For 
- Whites with `\(\chi^2 = 2.395\)`, <span class="boxed">we fail to reject `\(H_0\)`.</span>
- Blacks with `\(\chi^2 = 0.233\)`, <span class="boxed">we fail to reject `\(H_0\)`</span>.
It is also worth noting that two of the cells have expected counts less than 5 so results should be cautiously interpreted. It would likely be beneficial to repeat the study with a larger sample size.

</p>
</details>

<details><summary>5</summary>
<p>
a. <span class="boxed">We will make 2,973 errors</span> since we predict that all victims fall in the modal category (White) where
`\begin{align}
E_1 &= 6084 – 3111\\
   &= 2973
\end{align}`

b. For 
- White offenders, we could make <span class="boxed">373 errors</span>
- Black offenders, we could make <span class="boxed">493 errors</span>
- Other offenders, we would make <span class="boxed">42 errors</span> given `\(E_2 = 908\)`. 

c.  The proportional reduction in error is then 
`\begin{align}
\dfrac{2973 – 908}{2973} & \approx 0.6946
\end{align}`
This indicates a very strong relationship between the two variables. <span class="boxed">We can reduce the error in predicting victim’s race based upon race of offender by 69.46%</span>.

</p>
</details>

<details><summary>7</summary>
<p>
<div style="padding-left: 30px;">
We have
</div>
<div align="center">
<div style="width: 90%; margin:0 left;text-align: left;">
<table class="table" style="width: auto !important; margin-left: auto; margin-right: auto;">
 <thead>
  <tr>
   <th style="text-align:left;"> Race/Status </th>
   <th style="text-align:center;"> `\(f_0\)` </th>
   <th style="text-align:center;"> `\(f_e\)` </th>
   <th style="text-align:center;"> `\(f_0-f_e\)` </th>
   <th style="text-align:center;"> `\((f_0-f_e)^2\)` </th>
   <th style="text-align:center;"> `\(\dfrac{(f_0-f_e)^2}{f_e}\)` </th>
  </tr>
 </thead>
<tbody>
  <tr>
   <td style="text-align:left;"> White/First-Generation </td>
   <td style="text-align:center;"> 1742 </td>
   <td style="text-align:center;"> 1749.6 </td>
   <td style="text-align:center;"> -7.6 </td>
   <td style="text-align:center;"> 57.76 </td>
   <td style="text-align:center;"> 0.03 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> White/Nonfirst-Generation </td>
   <td style="text-align:center;"> 2392 </td>
   <td style="text-align:center;"> 2384.4 </td>
   <td style="text-align:center;"> 7.6 </td>
   <td style="text-align:center;"> 57.76 </td>
   <td style="text-align:center;"> 0.02 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Black/First-Generation </td>
   <td style="text-align:center;"> 102 </td>
   <td style="text-align:center;"> 93.5 </td>
   <td style="text-align:center;"> 8.5 </td>
   <td style="text-align:center;"> 72.25 </td>
   <td style="text-align:center;"> 0.77 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Black/Nonfirst-Generation </td>
   <td style="text-align:center;"> 119 </td>
   <td style="text-align:center;"> 127.5 </td>
   <td style="text-align:center;"> -8.5 </td>
   <td style="text-align:center;"> 72.25 </td>
   <td style="text-align:center;"> 0.57 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Native American/First-Generation </td>
   <td style="text-align:center;"> 41 </td>
   <td style="text-align:center;"> 36.4 </td>
   <td style="text-align:center;"> 4.6 </td>
   <td style="text-align:center;"> 21.16 </td>
   <td style="text-align:center;"> 0.58 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Native American/Nonfirst-Generation </td>
   <td style="text-align:center;"> 45 </td>
   <td style="text-align:center;"> 49.6 </td>
   <td style="text-align:center;"> -4.6 </td>
   <td style="text-align:center;"> 21.16 </td>
   <td style="text-align:center;"> 0.43 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Hispanic/First-Generation </td>
   <td style="text-align:center;"> 19 </td>
   <td style="text-align:center;"> 18.6 </td>
   <td style="text-align:center;"> 0.4 </td>
   <td style="text-align:center;"> 0.16 </td>
   <td style="text-align:center;"> 0.01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Hispanic/Nonfirst-Generation </td>
   <td style="text-align:center;"> 25 </td>
   <td style="text-align:center;"> 25.4 </td>
   <td style="text-align:center;"> -0.4 </td>
   <td style="text-align:center;"> 0.16 </td>
   <td style="text-align:center;"> 0.01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Asian American/First-Generation </td>
   <td style="text-align:center;"> 6 </td>
   <td style="text-align:center;"> 11.9 </td>
   <td style="text-align:center;"> -5.9 </td>
   <td style="text-align:center;"> 34.81 </td>
   <td style="text-align:center;"> 2.93 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> Asian American/Nonfirst-Generation </td>
   <td style="text-align:center;"> 22 </td>
   <td style="text-align:center;"> 16.1 </td>
   <td style="text-align:center;"> 5.9 </td>
   <td style="text-align:center;"> 34.81 </td>
   <td style="text-align:center;"> 2.16 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> `\(\chi^2 = 7.51\)` </td>
   <td style="text-align:center;">  </td>
   <td style="text-align:center;">  </td>
   <td style="text-align:center;">  </td>
   <td style="text-align:center;">  </td>
   <td style="text-align:center;">  </td>
  </tr>
</tbody>
</table>
</div>
</div>
<div style="padding-left: 30px;">
<span class="boxed">So `\(\chi^2 = 7.51\)` with `\(df = (2-1)\cdot(5-1) = 4\)` implying we would fail to reject `\(H_0\)`</span>. The probability of `\(\chi^2_{obt}\)` is between `\((0.20, 0.10)>\alpha = 0.05\)`.
</div>
</p>
</details>

<details><summary>13</summary>
<p>
<div style="padding-left: 30px;">
For
</div>
- Gender, the model is significant at the `\(0.01 \alpha\)` level, <span class="boxed">indicating a likely significant relationship between the variables</span>. Though males contribute to more violent onset, in proportional terms, females exhibit a higher prevalence rate, in that `\(18.32\)`% of females exhibit violent onset compared with `\(11.71\)`% of males. 

- Age at first offense, the model is significant at the `\(0.01 \alpha\)` level, <span class="boxed">indicating a likely significant relationship between age at first offense and violent onset</span>. Violent onset is more likely among the group 14 years and older ($14.74$%) than those less than 14 years of age at first onset ($9.67$%). 
</p>
</details>
-->
