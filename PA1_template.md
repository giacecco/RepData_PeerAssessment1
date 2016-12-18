# Reproducible Research: Peer Assessment 1

## Loading the data


```r
data <- read.table(unz("activity.zip", "activity.csv"), header=T, sep=",")
```

## Replacing any NA's with zeroes where necessary

```r
data$steps <- ifelse(is.na(data$steps), 0, data$steps)
```


## What is mean total number of steps taken per day?



## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
