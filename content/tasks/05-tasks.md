---
title: "The Normal Distribution"
linktitle: "Week 5: The Normal Distribution"
menu:
  tasks:
    parent: Homeworks
    weight: 5
type: docs
weight: 2
editor_options: 
  chunk_output_type: console
---
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
   <td style="text-align:center;font-weight: bold;"> 5 </td>
   <td style="text-align:left;"> 1, 2, 5, 6, 7, 8, 11, 12 </td>
   <td style="text-align:left;"> Social Statistics for a Diverse Society </td>
   <td style="text-align:left;"> 174-178 </td>
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


### Solutions

*Posted after class day and time next week.*

<!--


### Week 5 Problem Set




<details><summary>1</summary>
<p>





a. We are looking the area under the curve greater than `\(8\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-5-1.png" width="40%" />
The `\(z\)`-score for a person who watches more than 8 hr/day is given by
`\begin{aligned}
z &= \dfrac{8-2.97}{3.00}\\\\
&\approx 1.68
\end{aligned}`
So <span class="boxed">$z \approx 1.68$</span>.

b. We are looking the area under the curve less than `\(5\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-6-1.png" width="40%" />
The `\(z\)`-score for a person who watches less than 5 hr/day is given by
`\begin{aligned}
z &= \dfrac{5-2.97}{3.00}\\\\
&\approx 0.68
\end{aligned}`
So <span class="boxed">$z \approx 0.68$</span>. Since the area between `\(z=0.68\)` and `\(z=0\)` is `\(0.2517\)`, we have `\(0.5000+0.2517=0.7517\)`. This implies that `\(0.7517\cdot 1014 \approx\)` <span class="boxed">$762$ or `\(763\)` people watch television less than 5 hours/day</span>.

c. We have
`\begin{aligned}
Y&=2.97+1\cdot 3\\
&= 5.97
\end{aligned}`
implying that <span class="boxed">5.97</span> television hr/day corresponds to a `\(z\)`-score of `\(+1\)`.

d. We are looking at the area between `\(1\)` and `\(6\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-7-1.png" width="40%" />
The `\(z\)`-score for a person who watches more than 1 hr/day is given by
`\begin{aligned}
z &= \dfrac{1-2.97}{3.00}\\\\
&\approx -0.66
\end{aligned}`
with the area between the mean and `\(z=0.66\)` found to be `\(0.2454\)`.
<br>
The `\(z\)`-score for a person who watches less than 6 hr/day is given by
`\begin{aligned}
z &= \dfrac{6-2.97}{3.00}\\\\
&\approx 1.01
\end{aligned}`
with the area between the mean and `\(z=1.01\)` found to be `\(0.3438\)`.<br><br>
So the percentage of people who watch between 1 hr/day and 6 hr/day of television can be found by `\(0.2454 + 0.3438 = 0.5892\)`, or about <span class="boxed">$59\%$</span>.

</p>
</details>

<details><summary>2</summary>
<p>





a. The 95th percentile, or `\(0.9500\)` is approximately equivalent to `\(z=1.65\)`. So the number of women needing shelter is
`\begin{aligned}
Y&= 250+1.65\cdot 75\\
&= 373.75
\end{aligned}`
or about `\(374\)` women. Since this figure exceeds the total capacity of 350, there will <span class="boxed">not be enough space for all abused women on 95% of all nights</span>. at minimum, the city needs <span class="boxed">$374$</span> beds.

b. We are looking the area under the curve greater than `\(220\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-10-1.png" width="40%" />
The `\(z\)`-score for exceeding the capacity is given by
`\begin{aligned}
z &= \dfrac{220-250}{75}\\\\
&\approx -0.40
\end{aligned}`
The area below this value is `\(0.3446\)`, so the area exceeding this is `\(1 – 0.3446 = 0.6554\)`, or about <span class="boxed">$66\%$ of all nights</span> the number of women seeking shelter will exceed the capacity of 220.  

</details>
</p>

<details><summary>5</summary>
<p>

a. We are looking at the area between `\(12\)` and `\(16\)` for the Working class.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-11-1.png" width="40%" />
The `\(z\)`-score for a person with more than 12 years of education is given by
`\begin{aligned}
z &= \dfrac{12-13.05}{2.77}\\\\
&\approx -0.38
\end{aligned}`
with the area between the mean and `\(z=-0.38\)` found to be `\(0.1480\)`.<br><br>
The `\(z\)`-score for a person who watches less than 16 years of education is given by
`\begin{aligned}
z &= \dfrac{16-13.05}{2.77}\\\\
&\approx 1.06
\end{aligned}`
with the area between the mean and `\(z=1.06\)` found to be `\(0.3554\)`.<br><br> 
So the proportion of **working-class respondents** with 12–16 years of education can be found by `\(0.1480 + 0.3554 =\)` <span class="boxed">$0.5034$</span>.<br><br>
We are still looking at the area between `\(12\)` and `\(16\)` for the Upper class.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-12-1.png" width="40%" />
The `\(z\)`-score for a person with more than 12 years of education is given by
`\begin{aligned}
z &= \dfrac{12-15.48}{2.76}\\\\
&\approx -1.26
\end{aligned}`
with the area between the mean and `\(z=-1.26\)` found to be `\(0.3962\)`.<br><br>
The `\(z\)`-score for a person who watches less than 16 years of education is given by
`\begin{aligned}
z &= \dfrac{16-15.48}{2.67}\\\\
&\approx 0.19
\end{aligned}`
with the area between the mean and `\(z=0.19\)` found to be `\(0.0753\)`.<br><br>
So the proportion of **upper-class respondents** with 12–16 years of education can be found by `\(0.3962 + 0.0753 =\)` <span class="boxed">$0.4715$</span>.

b. We are looking the area under the curve greater than `\(16\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-13-1.png" width="40%" />
For working-class respondents, the `\(z\)`-score is given by
`\begin{aligned}
z &= \dfrac{16-12.05}{2.77}\\\\
&\approx 1.06
\end{aligned}`
The area between `\(z=1.06\)` and the tail is `\(0.1446\)` thus implying the probability of a **working-class respondent** having more than 16 years of education is <span class="boxed">$14.46\%$</span>.<br><br>
For middle-class respondents, the `\(z\)`-score is given by
`\begin{aligned}
z &= \dfrac{16-14.56}{2.95}\\\\
&\approx 0.49
\end{aligned}`
The area between `\(z=0.49\)` and the tail is `\(0.3121\)` thus implying the probability of a **middle-class respondent** having more than 16 years of education is <span class="boxed">$31.21\%$</span>.

c. We are looking the area under the curve less than `\(10\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-14-1.png" width="40%" />
For middle-class respondents, the `\(z\)`-score is given by
`\begin{aligned}
z &= \dfrac{16-14.56}{2.95}\\\\
&\approx 0.49
\end{aligned}`
The area beyond `\(z=0.63\)` and the tail is `\(0.2643\)` thus implying the probability of a **lower-class respondent** having more less 10 years of education is <span class="boxed">$26.43\%$</span>.

</details>
</p>

<details><summary>6</summary>
<p>





a. We are looking the area under the curve greater than `\(625\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-17-1.png" width="40%" />
For these high school graduates, the `\(z\)`-score is given by
`\begin{aligned}
z &= \dfrac{625-536}{102}\\\\
&\approx 0.87
\end{aligned}`
The area beyond `\(z=0.87\)` and the tail is `\(0.1992\)` thus implying the probability that a **high school graduate** having earning a score of more than 625 is <span class="boxed">$19.92\%$</span>.

b. We are looking the area under the curve between than `\(400\)` and `\(625\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-18-1.png" width="40%" />
For these high school graduates, the `\(z\)`-score for 625 is given by
`\begin{aligned}
z &= \dfrac{625-536}{102}\\\\
&\approx 0.87
\end{aligned}`
The area between the mean and `\(z=0.87\)` is `\(0.3087\)`.<br><br>
For these high school graduates, the `\(z\)`-score for 400 is given by
`\begin{aligned}
z &= \dfrac{400-536}{102}\\\\
&\approx -1.33
\end{aligned}`
The area between$z=-1.33$ and the mean is `\(0.4082\)`.<br><br>
Summing these proportions yields `\(0.3087+0.4082=0.7168\)`, or <span class="boxed">$71.68\%$</span> of the high school graduates earned a score between 400 and 625.

c. The 20th percentile, or `\(0.2000\)` is equivalent to `\(z=-0.84\)`. Thus the SAT ERW equivalency can be found by `\(536-0.84\cdot 102=450.32\)`, or a score of <span class="boxed">$450$</span>.

</details>
</p>

<details><summary>7</summary>
<p>





a. We have 
`\begin{aligned}
z &= \dfrac{150-100}{15}
&\approx 3.33
\end{aligned}`
or <span class="boxed">$z\approx 3.33$</span>.

b. We are looking the area under the curve greater than `\(150\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-21-1.png" width="40%" />
The area beyond `\(z=3.33\)` is `\(0.0004\)` implying that the percentage of scores above 150 is <span class="boxed">$0.04\%$</span>^[Which is the reason you don't notice any shading in the plot]. 

c. We are looking at the area between `\(85\)` and `\(150\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-22-1.png" width="40%" />
The `\(z\)`-score for a score of 85 is
`\begin{aligned}
z &= \dfrac{85-100}{15}\\\\
&\approx -1
\end{aligned}`
with the area between `\(z=-1\)` and the mean found to be `\(0.3413\)`.
<br>
The `\(z\)`-score for a score of 150 is
`\begin{aligned}
z &= \dfrac{150-100}{15}
&\approx 3.33
\end{aligned}`
with the area between the mean and `\(z=3.33\)` found to be `\(0.4996\)`.<br><br>
So the `\(0.3413 + 0.4996 = 0.8409\)`, or about <span class="boxed">$84\%$</span> of scores fall between `\(85\)` and `\(150\)`.

d. Scoring in the 95th percentile means that 95% of the sample scored below this level. This outcome can be calculated by `\(100 + 1.65\cdot 15 = 124.75\)`. So the IQ score that is associated with the 95th percentile is <span class="boxed">$124.75$</span>.

</details>
</p>


<details><summary>8</summary>
<p>





a. We are looking the area under the curve less than `\(400\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-25-1.png" width="40%" />
For these high school graduates, the `\(z\)`-score is given by
`\begin{aligned}
z &= \dfrac{400-531}{114}\\\\
&\approx -1.15
\end{aligned}`
The area beyond `\(z=-1.15\)` and the tail is `\(0.1251\)` thus implying that about <span class="boxed">$12.51\%$</span>of **high school graduates** hearned a score less than 400.

b. We are looking the area under the curve between than `\(600\)` and `\(700\)`.
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-26-1.png" width="40%" />
For these high school graduates, the `\(z\)`-score for 600 is given by
`\begin{aligned}
z &= \dfrac{600-531}{114}\\\\   
&\approx 0.61
\end{aligned}`
The area between the mean and `\(z=0.61\)` is `\(0.2291\)`.<br><br>
For these high school graduates, the `\(z\)`-score for 700 is given by
`\begin{aligned}
z &= \dfrac{700-531}{114}\\\\
&\approx 1.48
\end{aligned}`
The area between `\(z=1.48\)` and the mean is `\(0.4306\)`.<br><br>
Subtracting these proportions yields `\(0.4306-0.2291=0.2015\)`, or <span class="boxed">$20.15\%$</span> of the high school graduates earned a score between 600 and 700

c. For an earned score of `\(725\)` which is greater than the mean, we have
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-27-1.png" width="40%" />
From this we can calculate the `\(z\)`-score as 
`\begin{aligned}
z &= \dfrac{725-531}{114}\\\\   
&\approx 1.70
\end{aligned}`
The area beyond `\(z=1.70\)` is `\(0.0466\)`. So the percentile rank may be found by 
`\(1.000-0.0466 = 0.9535\)`, or `\(95.35\%\)` which implies the <span class="boxed">96th percentile</span>.

</details>
</p>

<details><summary>11</summary>
<p>





a. For an earned score of `\(990\)` which is greater than the mean, we have
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-30-1.png" width="40%" />
From this we can calculate the `\(z\)`-score as 
`\begin{aligned}
z &= \dfrac{990-981}{27.3}\\\\   
&\approx 0.33
\end{aligned}`
The area beyond `\(z=0.33\)` is `\(0.3707\)`. So the percentile rank may be found by 
`\(1.000-0.3707 = 0.6293\)`, or `\(62.93\%\)` which implies the 62nd percentile. So the team is <span class="boxed">not in the upper quartile</span>.

b. For the top 25%, or `\(0.0025\)`, the area beyond `\(z\)` is approximated by `\(z = 0.67\)`. The cutoff score is then `\(981+0.67\cdot 27.3\approx\)` <span class="boxed">$999.29$</span>.

c. As noted above, <span class="boxed">$z = 0.67$</span>.

</details>
</p>

<details><summary>12</summary>
<p>

a. For **Team A** an ***eligibility criterion*** score of `\(971\)` is given by
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-31-1.png" width="40%" />
From this we can calculate the `\(z\)`-score as 
`\begin{aligned}
z &= \dfrac{971-983}{33}\\\\   
&\approx -0.36
\end{aligned}`
For **Team A** a ***retention criterion*** score of `\(958\)` is given by
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-32-1.png" width="40%" />
From this we can calculate the `\(z\)`-score as 
`\begin{aligned}
z &= \dfrac{958-976}{34.9}\\\\   
&\approx -0.52
\end{aligned}`
For **Team B** an ***eligibility criterion*** score of `\(987\)` is given by
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-33-1.png" width="40%" />
From this we can calculate the `\(z\)`-score as 
`\begin{aligned}
z &= \dfrac{987-983}{33}\\\\   
&\approx 0.12
\end{aligned}`
For **Team B** a ***retention criterion*** score of `\(970\)` is given by
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-34-1.png" width="40%" />
From this we can calculate the `\(z\)`-score as 
`\begin{aligned}
z &= \dfrac{970-976}{34.9}\\\\   
&\approx -0.17
\end{aligned}`
So <span class="boxed">Team B is better on both eligibility and retention than Team A</span>. 

b. For **Team B** a ***retention criterion*** score of `\(z=-0.17\)` is below the mean and the corresponding proportion can be viewed by
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-35-1.png" width="40%" />
which is the area between `\(z\)` and the tail, or <span class="boxed">$0.4325$</span>.

c. For **Team A** an ***eligibility criterion*** score of `\(z=-0.36\)` is below the mean and the corresponding proportion can be viewed by
<img src="/tasks/05-tasks_files/figure-html/unnamed-chunk-36-1.png" width="40%" />
which is the area between `\(z\)` and the tail, or `\(0.3594\)` implying about the <span class="boxed">35th percentile</span>.

</details>
</p>
-->
