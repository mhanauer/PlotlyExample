---
title: "Data Cleaning and Analysis in R"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
Try ploty stuff
```{r}
library(plotly)
Sys.setenv("plotly_username"="MattHanauer")
Sys.setenv("plotly_api_key"="DGsDtq4C3anyNxREUJfl")
outcome = rnorm(100)
time = rep(1:10,10)
dat = data.frame(outcome, time)
p = plot_ly(data = dat, x = time, y = outcome)
api_create(p)
```

