---
title       : Diapositivas slidify    
subtitle    : 
author      : Laura C. Neira
job         : Estudiante de estadistica
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


# Tabla

Nombre      | Estatura | Peso
------------| ------------|------------
Juan | 1.72 | 65
Matheo | 1.65| 62
Isabella | 1.60 | 60
Juliana | 1.55| 50
Sofia | 1.50| 45
Hector | 1.60| 55
Santiago | 1.58| 55

--- .class #id 

# Imagen
![Logo](descarga.jpg) 

--- .class #id 

# ggplot2

```r
require(ggplot2)
qplot(wt, mpg, data = mtcars)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png)

--- .class #id 
