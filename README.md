# Streetmap-with-ggplo2
Here show you how make a street map  you city 
---
title: "Streetmaps with ggplot2"
author: "Ivan Leonel Vasquez R."
date: "December 7, 2019"
output:
  html_document: default
  pdf_document: default
  word_document: default
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)

```

## Map Barquisimeto-Cabudare, Venezuela.

Here i show you how following step by step the tutorial instruction give in <http://ggplot2tutor.com/streetmaps/streetmaps/>, we can will generate code in R (ggplot2) which output are streets maps of our city.

Aquí te muestro cómo siguiendo paso a paso las instrucciones del tutorial<http://ggplot2tutor.com/streetmaps/streetmaps/>, podemos generar código en R (ggplot2) cuyo resultado son mapas de calles de nuestra ciudad.

This work was made for the City Barquisimeto-Cabudare, the city where I currently live in the Venezuela country.

we needs to instal ***omsdata*** and ***ggplot2*** packages, ggplot2 is in **tidyverse**, so is enough instal it.


```{r cars, include=TRUE}

library(tidyverse)
library(tinytex)
```