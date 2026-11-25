# Introduction to Statistical Process Control Charts in Healthcare Using R

A practical, hands-on course for data scientists and analysts.

This course takes you from understanding variation and interpreting SPC charts to constructing charts using R. You will first learn the underlying principles by building charts using base R, then move on to using the `qicharts2` package for practical applications. Finally, we explore more specialised chart types and reproducible reporting.

The course is based on the book by [Jacob Anhøj and Mohammed A Mohammed](https://spc4hc.org/about.html): **Mastering Statistical Process Control
Charts in Healthcare**, available [online](https://spc4hc.org/book/) and on
[Amazon](https://amzn.eu/d/00RI5hJu).

## Course Outline

### Day 1: Understanding variation using SPC charts

**Chapters 1-4**

* Understanding variation.
  - common cause variation.
  - special cause variation.

* Understanding SPC charts.
  - anatomy and physiology of SPC charts.
  - common types of SPC charts -- The Magnificent Seven.
  - common patterns of change in SPC charts.
  - tests for special cause variation.

* Using SPC charts in healthcare.
  - reconciling the voice of the customer and the voice of the process.
  - investigating signals of special cause variation using the Pyramid Model of Investigation.

### Day 2: Constructing SPC charts using base R

**Chapters 5-8**

* Creating random data for testing.

* Plotting and analysing run charts.

* Adding control limits.

* Reading data from csv files.

* Creating the `spc()` function to handle the most common types of data: measurements, counts, rates, and proportions: I C U P &#128540;

### Day 3: SPC charts using `qicharts2` for R

**Chapter 10**

* Introducing `qicharts2`.

* Constructing the "Magnificent Seven" SPC charts with `qicharts2`:
  - I and MR charts for individual measurements.
  - X-bar and S charts for subgrouped measurements.
  - C charts for event counts.
  - U charts for event rates.
  - P charts for case proportions.

* Using the freeze and part arguments to fix the baseline period or divide the chart into multiple parts.

* Creating multivariate plots (small multiples).

### Day 4: Additional SPC charts for specialist purposes

Chapters 12-16

* SPC charts for categorical subgroups (funnel plots).

* SPC charts for rare events:
  - G charts for opportunities between cases.
  - T charts for time between events.

* P and U prime charts for rates and proportions with very large subgroups:

* I prime charts for aggregated data with varying subgroup sizes.

* Introducing reproducible and reliable reports and dashboards using Rmarkdown and Shiny.

## Course Dates

* Tuesday 6 April 2027

* Tuesday 13 April 2027

* Tuesday 20 April 2027

* Tuesday 27 April 2027

All days from 13:30 to 16:45 UK time

## Course Preparation

* Essential R knowledge you should be familiar with:
  - data types (numbers, characters, dates)
  - data structures (vectors, lists, data frames)
  - functions and documentation
  - reading data from CSV-files
  - performing arithmetic operations (+, -, *, /)
  - plotting (points, lines, bars, histograms)

* Software that must be installed before Day 2:
  - [R](https://www.r-project.org/) (&ge; 4.6.2)
  - [RStudio](https://docs.posit.co/ide/user/download.html) (&ge; 2026.10.1+239)

* Recommended reading (The White Book).
  - Anhøj & Mohammed (2026) [Mastering Statistical Process Control Charts in Healthcare](https://spc4hc.org/book/).
  
* Further resources: 
  - SPC for Healthcare website: https://spc4hc.org
  - Course materials including datasets and R code are available at: https://github.com/anhoej/spc4hc_intro

## Home Assignments

To prepare for and consolidate your learning, please complete the assignments after each course day:

### Day 1

1. Get R (&ge; 4.6.2) and RStudio (&ge; 2026.10.1+239) up and running on your PC (https://youtu.be/orjLGFmx6l4),

1. Run this command to check that everything works: `plot(rnorm(24), type = 'o')`

### Day 2

1. Download the course GitHub repository: https://github.com/anhoej/spc4hc_intro. 

1. With the [...] dataset, create at least one run chart and one or more control charts using the `spc()` function.

1. Install the [`qicharts2`](https://anhoej.github.io/qicharts2/) package (&ge; 0.8.1) and check that it works with this command: `qicharts2::qic(rnorm(24))`.

### Day 3

1. With the [...] dataset and using `qicharts2`, construct one or more examples of each of the Magnificent Seven SPC charts.

1. Construct a one-way faceted SPC chart from the ... data.

### Day 4

1. Go forth and change the world!

## Daily programme

All times are approximate.

* 13:30 - 13:55 Session 1
* 13:55 - 14:00 Break
* 14:00 - 14:25 Session 2
* 14:25 - 14:30 Break 
* 14:30 - 14:55 Session 3
* 14:55 - 15:15 Break
* 15:15 - 15:40 Session 4
* 15:40 - 15:45 Break
* 15:45 - 16:10 Session 5
* 16:10 - 16:15 Break
* 16:15 - 16:45 Recap, Q&A and assignments
