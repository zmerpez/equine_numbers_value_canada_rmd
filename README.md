# Historical horse population in Canada
Author: Tiffany Timbers

Report that explores the historical population of horses in Canada between 1906 and 1972 per province.

## Dependencies:
- R and R packages:
  - tidyverse
  - knitr
  - here

## Instructions to reproduce report:
1. clone or download this repository
2. open RStudio and set this project root as the working directory
3. Open `doc/hist_horse_pop.Rmd` and click the "knit" button or run type `rmarkdown::render("doc/hist_horse_pop.Rmd")` in the R console.
4. Optionally, select "Knit with Parameters" or rmarkdown::render("doc/hist_horse_pop.Rmd", params = list(province = <PROVINCE>)) to change the province to focus on for figure 2.
