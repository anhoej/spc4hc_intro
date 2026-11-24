# Mastering Statistical Process Control Charts in Healthcare

## -- a practical, hands-on course for data scientist and analysts

This course is based on our new book: Mastering Statistical Process Control
Charts in Healthcare, available [online](https://spc4hc.org/book/) or on
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

**Home assignment**:

1. Get R and RStudio up and running on your PC.

### Day 2: Constructing SPC charts using base R

**Chapters 5-8**

* Creating random data for testing.

* Plotting and analysing run charts.

* Adding control limits.

* Reading data from csv files.

* Creating the `spc()` function to handle the most common types of data: measurements, counts, rates, and proportions: I C U P &#128540;

**Home assignments**: 

1. Create at least one run chart and one or more control charts using the `spc()` function with your own data.

1. Install the [`qicharts2`](https://anhoej.github.io/qicharts2/) package.
 
### Day 3: SPC charts using qicharts2 for R

**Chapter 10**

* Introducing `qicharts2`.

* Constructing the "Magnificent Seven" SPC charts with `qicharts2`:
  - I and MR charts for individual measurements.
  - Xbar and S charts for subgrouped measurements.
  - C charts for event counts.
  - U charts for event rates.
  - P charts for case proportions.

* Using the freeze and part arguments to fix the baseline period or divide the chart into multiple parts.

* Creating multivariate plots (small multiples).

**Home assignment**:

1. With your own data and using `qicharts2`, construct a one-way faceted plot with and without centre line and limits frozen to a baseline period.
 
### Day 4: Additional SPC charts for specialist purposes

Chapters 12-16

* SPC charts for categorical subgroups (funnel plots).

* SPC charts for rare events:
  - G charts for opportunities between cases.
  - T charts for time between events.

* P and U prime charts for rates and proportions with very large subgroups:

* I prime charts for aggregated data with varying subgroup sizes (and much more).

* Introducing reports and dashboards using Rmarkdown and Shiny.

**Home assignment**:

1. Go forth and change the world!

## Course dates

* Tuesday 06th April 2027

* Tuesday 13th April 2027

* Tuesday 20th April 2027

* Tuesday 27th April 2027

All days from 13:00 to 16:30 UK time

## Requirements

* The "White" Book: [Mastering Statistical Process Control Charts in Healthcare](https://spc4hc.org/book/).

* Have [R](https://www.r-project.org/) (&ge; 4.6.2) and [R-studio](https://docs.posit.co/ide/user/download.html) (&ge; 2026.10.1+239) installed and working.

* Basic familiarity with R
  - data types (numbers, characters, dates)
  - data structures (vectors, lists, data frames)
  - functions
  - reading data from csv-files
  - performing arithmetic operations (+, -, *, /)
  - plotting (points, lines, bars, histograms)
