---
title: "Reproducible Research: Peer Assessment 1"
output: 
  html_document:
    keep_md: true
---


```
## Warning: package 'data.table' was built under R version 3.6.2
```

## Download the CSV file from online URL



## Now read the downloaded file in to a DataTable variable


```
##    steps       date interval
## 1:    NA 2012-10-01        0
## 2:    NA 2012-10-01        5
## 3:    NA 2012-10-01       10
## 4:    NA 2012-10-01       15
## 5:    NA 2012-10-01       20
## 6:    NA 2012-10-01       25
```

## Calculate total no of steps taken each day. This is calculated by taking standard deviation



## Now plot the toal_steps_pd using ggplot- histogram

```
## Warning: Removed 8 rows containing non-finite values (stat_bin).
```

![](PA1_template_files/figure-html/unnamed-chunk-4-1.png)<!-- -->

## Calculate mean and median of total no of steps taken each day

```
##    mean_steps median_steps
## 1:   10766.19        10765
```

## 5-minute interval that, on average, contains the maximum number of steps


## Plot time series plot for average number of steps taken
![](PA1_template_files/figure-html/unnamed-chunk-7-1.png)<!-- -->


## Imputing NA values from the dataTable





### Total steps taken per day


### mean and median total number of steps taken per day

```
##    Mean_Steps Median_Steps
## 1:    9354.23        10395
```

```{}

Important: Here you can see that mean and median has changed with and without NA values in the data set
```

## Difference between activities between weekday and weekends


```
##     steps       date interval Day of Week weekday or weekend
##  1:    NA 2012-10-01        0      Monday            weekday
##  2:    NA 2012-10-01        5      Monday            weekday
##  3:    NA 2012-10-01       10      Monday            weekday
##  4:    NA 2012-10-01       15      Monday            weekday
##  5:    NA 2012-10-01       20      Monday            weekday
##  6:    NA 2012-10-01       25      Monday            weekday
##  7:    NA 2012-10-01       30      Monday            weekday
##  8:    NA 2012-10-01       35      Monday            weekday
##  9:    NA 2012-10-01       40      Monday            weekday
## 10:    NA 2012-10-01       45      Monday            weekday
```

## Plotting for Weekend and weekdays activity patterns

![](PA1_template_files/figure-html/unnamed-chunk-13-1.png)<!-- -->
