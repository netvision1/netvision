---
title: "This is a test post for my blog"
author: "NetVision.me"
date: '`r Sys.Date()`'
output: html_document
---
```{r, echo=TRUE}
summary(web-development)
```
library(ggplot2)
ggplot(mpg, aes(displ, hwy)) +
  geom_point(aes(color = class)) +
  geom_smooth(se = FALSE, method = "loess") +
  labs(
    title = "HOW TO HOST YOUR OWN DOMAIN USING GITHUB",
    subtitle = "Connect your own domain and using GitHub as a Hosting for your static website",
    caption = "GitHub"
  )
