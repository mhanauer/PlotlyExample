---
title: "PlotlyExample"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
Try ploty stuff
```{r}

library(plotly)
Sys.setenv("MattHanauer"="MattHanauer")
Sys.setenv("DGsDtq4C3anyNxREUJfl"="DGsDtq4C3anyNxREUJfl")
library(plotly)
p <- plot_ly(midwest, x = ~percollege, color = ~state, type = "box")
plotly_POST(p, filename = "r-docs-midwest-boxplots")
```

