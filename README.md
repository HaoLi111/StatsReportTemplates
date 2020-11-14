# the-Fundamental-Templates-of-R

## Aim

We wanted this to be the most concise way of summarizing R functions. I was able to create these templates, but they still need to be enhanced, that says, I need your help.

We aim to summarize most R functions for statistics and data-sciences in the most concise markdown templates. They can either serve as modules or tutorials to borrow from or the building blocks for future plan to automatic report writing. The importance of visualization is stressed as it eradicates the barrier between statisticians and the non-professional report readers.

## Prerequisies

20+ packages will be required but the most crucial ones are listed below (and I recommend that you use RStudio IDE):

 - tidyverse
 - GGally
 - knitr
 - caret
 - Plot3D
 - Hmisc
 - Forecast
```r
install.packages("knitr")
install.packages("ggplot2")
install.packages("lattice")
install.packages("rgl")
install.packages("plot3D")
install.packages("plot3Drgl")
install.packages("GGally")
install.packages("tiff")
install.packages("tidyverse")
install.packages("datatable")
install.packages("reshape")
install.packages("caret")

```
## Coverage

The task to analyze tidy data frame is prioritized as most high dimensional data can be sanitized to the form with each column representing a variable, each row an observation. However, due to the variety of fields these methods can be applied to, and the underlying theories that may be lurking, which are not purely empirical, non-tidied data, such as time series, matrices, images are also covered. 

### Discriptive and exploratory analysis of tidied dataframe
Done. Suggestions are welcome
### Predictive modeling
Help needed! Tune models and comparisions with caret and visreg in a more elegant way.
### 1 variable time series analysis with seasonality
Working on this part.
### Image statistics and visualization
Basic functions done. But matrix processing is better to be handled by wrappers because R's matrix operation is slow (even with JIT).
### Non-linear fitting, non-linearity test
Working on this part.
### Multi-variable time-series analysis
Help needed.
## Recommended materials

There is generally no manual for the files in this repository, to be able to understand what each part of the markdown files are doing, It is useful to look up the recommended materials.


 - Applied Predictive Modeling by M. Kuhn
 - Data Visualization with ggplot2 on DataCamp
 - Talks by Hadley Wickham on youtube(summarize later)
 - The Art of R programming by N. Matloff
 - Data Mining with R by L. Torgo and its relevant code
 - Mathematical Modeling by M. Meerschaeart and its relevant code
 - Chaos edited by A. Holden (this seems less related unless you want to analyse the NL time series)
 
