# Session-4.3-assignment-rahul-sharma
Acagild session 4.3 assignment 

1. States = rownames(US Arrests)

Get states names with ‘w’.

Get states names with ‘W’.

Ans 1. ->

Get states names with ‘w’. ->

library(datasets)

x<-USArrests[order(USArrests$Murder),]

x<-rownames(x[46:50, ])

tolower(x)

Get states names with ‘W’. ->

library(datasets)

x<-USArrests[order(USArrests$Murder),]

x<-rownames(x[46:50, ])

toupper(x)


2. Prepare a Histogram of the number of characters in each US state

Ans 2. ->

hist(nchar(states), main = "Histogram",

xlab = "number of characters in US State names")
