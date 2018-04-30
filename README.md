# weather-pollution_analysis

library(readr)
library(tidyr)
library(dplyr)
library("reshape2")
library("ggplot2")
library(RCurl)
x <- getURL("https://raw.github.com/aurazhang/weather-pollution_analysis/weather_pollution_data.csv")
weather_pollution_data <- read.csv(text = x)
head(weather_pollution_data)
