---
layout: single
title: Analyzing Toggl data with PowerBI
show_date: true
date: 2023-03-03
date_format: "%Y-%m-%d"
permalink:
excerpt:

categories: [Article]
tags: [productivity]

sidebar:
  nav: "sidebar"

toc: true
toc_sticky: true
---

## Download Toggl data
- In the Reports tab, click on Detailed, then choose the time range
![](https://i.imgur.com/hvdYSKg.png)

- Download .csv file (top right)
![](https://i.imgur.com/UovXqGO.png)

## Import Toggl Data in PowerBI
![](https://i.imgur.com/noDxhzF.png)
- Click on "Paste data into a blank table"
- Select all your data from the .csv file, click on "Column 1" and paste your data

## Clean and edit your data
- You technically only need the Start date
	- Won't really use Start time, End date, End time
- Change Duration column into Duration value type
![](https://i.imgur.com/xa7xKvZ.png)
- Convert to hours
![](https://i.imgur.com/2PTdPE2.png)
- Close and apply from the Home tab

## Adding columns
### Add a week column
- In data view
![](https://i.imgur.com/eiS6UUS.png)
### Rename the column and add formula
![](https://i.imgur.com/Ra4lEwC.png)

## Put everything together
- Choose the 100% Stacked column chart in Visualizations
	- Then select your data and put them in the corresponding axes

	![](https://i.imgur.com/21dFZtj.png)

- You should have a weekly breakdown of your Projects
![](https://i.imgur.com/KjjlfWW.png)

