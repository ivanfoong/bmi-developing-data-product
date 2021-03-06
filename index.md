---
title       : BMI Calculator for Free!
subtitle    : Because everyone needs to know their own BMI
author      : Ivan Foong
job         : Data Scientist Noob level
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Wikipedia's BMI explaination

The *body mass index* (*BMI*), or *Quetelet index*, is a measure of relative weight based on an individual's mass and height.

Devised between 1830 and 1850 by the Belgian polymath [Adolphe Quetelet](http://en.wikipedia.org/wiki/Adolphe_Quetelet) during the course of developing "social physics", it is defined as the individual's body mass divided by the square of their height – with the value universally being given in units of kg/m2

More at <http://en.wikipedia.org/wiki/Body_mass_index>

By filling your height and weight at <http://ivanfoong.shinyapps.io/bmi-developing-data-product>, you can easily find out your own BMI!

--- .class #id 

## BMI Formula (Metric)

![BMI formula](http://www.build-muscle-and-burn-fat.com/images/BMI_formula_metric.png)


```r
height = 1.8
weight = 80
bmi = weight/(height*height)

# The BMI for a person 1.8m in height and 80kg in weight is:
bmi
```

```
## [1] 24.69
```



BMI Formula Image from <http://www.build-muscle-and-burn-fat.com>

--- .class #id 

## BMI Classification

| Category    | BMI range   |
|:-----------:|:-----------:|
| Underweight | < 18.5      |
| Normal      | 18.5 - 22.9 |
| Overweight  | 25 - 29.9   |
| Obese       | > 30        |

--- .class #id 

## Notes

My BMI calculator can be found at <http://ivanfoong.shinyapps.io/bmi-developing-data-product>

The BMI formula and classification range is as mentioned at <http://www.freebmicalculator.net/>

--- .class #id 
