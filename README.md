# Grafico_ggplop_1
Primer ejemplo

---
title: "R Notebook"
output: html_notebook
---

Nuestro primer gráfico en ggplot2

```{r}
  # Load ggplot2
  library(ggplot2)
  ggplot(data = mpg) + # crea una capa con el dataset
  geom_point(mapping = aes(x = displ, y = hwy)) # añade otra capa de puntos
```
