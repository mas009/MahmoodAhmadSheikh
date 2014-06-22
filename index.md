---
title       : Simulation of Geyser Eruption Duration
subtitle    : A Shiny App Approach
author      : Mahmood A. Sheikh
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

In this presentation, we will show you an application that simulates a geyser eruption duration. There are many ways in which you will be able to see how things change when you choose a different option for the simulation. These are explained below:

- You can change the number of bins to be shown on the histogram using a dropdown   combo-box button
- You can see the individual observations using a check box provided for this    purpose
- You can see the density estimate using another check box provided for this purpose
- You can also vary bandwith for density estimate using the slider control provided for this purpose
- A complete explanation of the User Interface can be seen on the next slide

--- 

## Application Explanation

When you first open the application you will see a histogram of the geyser eruption duration with 20 bins selected by default. Moreover, you see two check-boxes to refine your choices both of them unchecked by default. We will give details of all the user interface choices one by one below:

- First of all there is a drop-down combo box that let you select how many bins you would like to see in the histogram. When the page is loaded a histogram appears with 20 bins by default. You can change the appearance of the histogram from the choices provided there. It also explain that how the shape of histogram changes as the number of bins are increased or decreased.

- You can see that as the number bins are increased or decreased the shape of histogram shows a shape of more or less normal distribution according to more or less number of bins selected respectively as is expected according to statistical theory.

--- 

## Application Explanation Cont'd

- Then there is a check-box with title "Show individual observations" which when selected let you see the actual points of observations upon which the histogram have been built.

- Another check-box with title "Show density estimate" let you see the density of observation points that explain area under the curve for more points or less points.

- When the "Show density estimate" check-box is selected, there appears another user interface gadget namely "Bandwidth adjustment" that let you see how the density estimate changes its position according to the range provided in this gadget. By default it is set at 1, among the range between 0 - 2. Use this slider to see what happens when it is moved between 0 and 2.

---

## Thank you


A big thanks from me to be patient during this presentation. I hope I have not bored you too much and you may have learnt something useful.

## Cheers ...



