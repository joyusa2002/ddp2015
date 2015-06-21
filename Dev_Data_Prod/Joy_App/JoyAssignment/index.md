---
title       : Developing Data Product App
subtitle    : Histogram for mpg using mtcars dataset
author      : Joy Mehta
job         : Consultant
framework   : io2012       # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Title

Developing Data Product App
Histogram for mpg using mtcars dataset

By - Joy Mehta

--- .class #id 

## Introduction

The purpose of this project is to prepare a Moving Histogram. The data used was obtained from R dataset package of "mtcars". The analysis and illustration is for miles per gallon or mpg. Visual comparison is by way of the histogram with slider. 

--- .class #id 

## Project Overview

This Shiny application is created for the Coursera program's Developing Data Products project. The dataset provided is originally from Motor Trend Road Tests (1974 Motor Trend US magazine) with 32 observations and 11 variables.
The programming and computations are performed using RStudio 3.1 series 0.98.1102 package. 

--- .class #id

## Application & Function

The application is created with the standard ui.R and server.R codes using shiny package to prepare panels and sidebars as needed. The slider performs for a maximum of 40 bins and the plot output is by way of the "hist" function.
The hist function is shown below.

```r
?hist
hist
```

```
## function (x, ...) 
## UseMethod("hist")
## <bytecode: 0x000000000975a960>
## <environment: namespace:graphics>
```
The above code shows what histogram does.

--- .class #id

## Summary & Publication

The project was completed to meet the assignment goals and is published on RPubs.



