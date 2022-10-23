---
title: "An Unbiased Biased View on Bayesian Statistics"
linktitle: "Week 14: An Unbiased Biased View on Bayesian Statistics"
toc: true
output:
  rmarkdown::html_document:
    toc: true
menu:
  extras:
    parent: Examples
    weight: 14
type: docs
weight: 1
editor_options: 
  chunk_output_type: console
---

<script src="/rmarkdown-libs/kePrint/kePrint.js"></script>

<link href="/rmarkdown-libs/lightable/lightable.css" rel="stylesheet" />

{{% aes-header %}}

### Veritasium + Crash Course Statistics

This week we’re doing something a little different. We first have a video from a science communicator named Derek Muller on his excellent YouTube channel [Veritasium](https://www.youtube.com/channel/UCHnyfMqiRRG1u-2MsSQLbXA). At the end, there will be two videos from Crash Course Statistics that go deeper into the statistics part of the Bayesian approach.

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/R13BD8qKeTg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
</p>

### Note

To be honest most of you will leave this class likely not thinking or caring about the underlying methodological and philosophical disagreement that exists between the two types of statisticians explained below. So why does it matter? In a nutshell, we’re at a point in history where the dominant approach will affect your everyday life ranging from credit to Internet speeds to predictions/reviews in sports to any other aspect where data, in particular “big data” is present. So while you may not be personally invested in the statistical approach that becomes the *standard*, your life will surely be affected and its not a bad idea to know the underlying reasons behind it.

<center>
<img alt="Statistician Deathmatch" src="/img/examples/statistician_deathmatch.png" width = "50%">
</center>

### Full Disclosure

Firstly I consider myself a Bayesian statistician, so there is an inherent bias and uncertainty in this writing which will be apparent later. The benefit here is that unlike a frequentist approach that rejects or minimizes bias and favors outcomes with certainty, Bayesians recognize and utilize bias in their statistics where both uncertainty exists as part of the problem, and solutions are given as multiple possibilities with varying levels of probabilities[^1].

### Bit of History

The Bayesian way of thinking was quite popular in the 18th and 19th centuries, but fell out of favor in the 20th century which gave way to the frequentists. During that time, the few Bayesian statisticians that were active were often shunned and even ridiculed by academics and practitioners alike. It looked like we knew everything about the foundation of statistics and anything that needed a new approach was simply a matter of furthering that viewpoint. But in the mid to late 2000 large sets consisting of a combination of structured, semistructured, and unstructured data - aka “big data” - began to pop up everywhere. However technology, in particular computing technology was simply not able to handle and analyze these data sets. Moreover for most of the public, computers were just a means to create or run an application - the idea that they could do anything beyond that was deemed to be science fiction that could be science one day in the distant future. But as life would have it, not only were we able to figure out how to teach a computer to learn and make decisions - aka machine learning (ML) - many ML algorithms were significant improved by attaching prior beliefs about how a data set should be looked at creating a situation where a person get choice of multiple statistical models and are able to pick the one that works out the best for an analyses.

### A Line is Drawn

Statisticians and those who practice statistics are at odds on how the world works. One group - the frequentists - think deductively and see probability as a means for finding a single defined outcome while another - the Bayesians - think inductively and use probability to describe the chance of many possible outcomes.

#### Frequentist Statisticians

Statisticians who view ***the world as deterministic, do not include subjectivity, and see probabilities as a way to explain how random events would look after a bunch of trials*** are known as **frequentist statisticians**. To show this through a statistical lens, let’s look at the traditional coin flipping example: As a frequentist statistician, we would

1.  first suppress any prior ideas of how the outcome should look;
2.  then flip a coin over and over and record the results; and
3.  find that after enough flips that while we will likely never get 50-50 odds, the data shows that we’re heading that way so with the idea if we flipped that coin an infinite number of times, that’s the true outcome.

This is the idea of something being deterministic where probabilities are used to describe a *fixed value* which in this case is always going to be 50-50. For any social scientists, the epistemological perspective is that frequentist for the most part believe in a single truth.

#### Bayesian Statisticians

Statisticians who view ***the world as probabilistic, allow for prior beliefs about a phenomena, and update the probability of those beliefs with new evidence*** are known as **Bayesian statisticians**. To again show this through a statistical lens, let’s look at the traditional coin flipping example: As a Bayesian statistician, we would

1.  first have a prior belief of what the probability of getting a heads or tails is say 50-50.
2.  then flip a coin over and over and record the results; and
3.  find that after enough flips that we will never get to the 50-50 odds implying that there are multiple possible outcomes, each with its own associated probability.

This is the idea of something being deterministic where probabilities are used to describe *multiple values* which in this case may be 50-50, but could also be 40-60, 60-40, 20 - 80 and so on, each associated with some chance of being true. For any social scientists, the epistemological perspective is that Bayesian for the most part believe in multiple truths with some more likely than others.

### Mostly Non Stats Example

Rather than provide an example that uses a bunch of statistics, let’s look at it practically.

*Situation*: You have misplaced your iPhone somewhere in your apartment or home. You can use the Find My app ® to find it and hear beeping.

*Problem*: Which room in your apartment or home should you search?

*Approaches*

-   Frequentist: You hear the phone beeping and you have some approach using a mental model to help figure out what room the beeping is coming from. So you used ***inferences from the beeps*** to locate the room in your home you must search to find the phone.

-   Bayesian: You hear the phone beeping and along with some approach using a mental model, you also know all of the rooms you have misplaced the phone before which combined help to figure out what room the beeping is coming from. So you used ***inferences from the beeps*** and ***prior knowledge*** to locate the room in your home you must search to find the phone.

### Table of Differences

There are multiple differences in how the sides view not just how problems should be viewed and solved, but on the nature of reality itself. The table below gives some overarching ones.

<table class="table" style="width: auto !important; margin-left: auto; margin-right: auto;">
<thead>
<tr>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Type
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Information Used
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
What is Random?
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Type of Reasoning
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Terminology
</th>
<th style="text-align:left;color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Observed Data
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;width: 5em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
<i>Frequentist</i> statistician
</td>
<td style="text-align:left;width: 20em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Outcomes derived strictly from experiments
</td>
<td style="text-align:left;width: 20em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
<i>Observed data</i>. Any data that has been collected from an experiment
</td>
<td style="text-align:left;width: 5em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
<i>Deductive</i> logic
</td>
<td style="text-align:left;width: 20em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Common terms like <i>p-value</i>, <i>significant</i>, <i>null hypothesis</i>, and <i>confidence interval</i>
</td>
<td style="text-align:left;width: 10em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Unknown and comes only from experiments
</td>
</tr>
<tr>
<td style="text-align:left;width: 5em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
<i>Bayesian</i> statistician
</td>
<td style="text-align:left;width: 20em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Prior beliefs about what the truth might be which are interatievly updated as experiments progress
</td>
<td style="text-align:left;width: 20em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
<i>Population parameters</i>. Any summary number, like an average or percentage, that describes the entire population
</td>
<td style="text-align:left;width: 5em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
<i>Inductive</i> logic
</td>
<td style="text-align:left;width: 20em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Uncommon terms like <i>prior probability</i>, <i>noninformative priors</i>, and <i>credible intervals</i>
</td>
<td style="text-align:left;width: 10em; color: #ffffff !important;background-color: #212121 !important;vertical-align: middle !important;">
Known since we already know what we know
</td>
</tr>
</tbody>
</table>

### So Who is Right?

We honestly just don’t know right now. Similar to physics where there are two seemingly incompatible laws governing the universe - *relativity* for large and *quantum* for small objects, respectively - statisticians have the same difficulty regarding inferences. The frequentist thinking is by far the dominant approach because it involves fairly “simple” and concrete calculations that can be tested and verified when explaining the phenomena around us. In fact, the approach aligns with the idea of certainty that humans like and need to make sense of the world, but there is a limit to what this approach can explain and that has not been more apparent than with computing. Practically speaking ignoring the human element in a study absolutely makes it easier to perform analyses, but the very act of removing it has an affect from start to finish that results in outcomes that are at the very least imprecise and at most harmful.

The actual explanation for which side is right is likely some combination of both approaches - yet there may also be another method that can unify both into an all encompassing statistical approach that we just haven’t considered yet or maybe both approaches are wrong and we need to rethink statistics from the ground up. For now all we have are these two somewhat related yet also contradictory views on how the world works.

*So it may be that frequentist statistics is a needed field in order to get to the Bayesian way of looking at the world similar to needing an understanding of descriptive statistics prior to moving into inferential.*

#### Frequentist Statistics

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/OyddY7DlV58" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
</p>

<br>

#### Bayesian Statistics

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/oZCskBpHWyk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen>
</iframe>
</p>

[^1]: Fun fact: The fact you are able to view this exact page right now is based on [based on probability](https://www.americanscientist.org/article/programs-and-probability)
