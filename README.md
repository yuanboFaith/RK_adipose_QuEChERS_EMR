## Development and validation of a micro-QuEChERS method with high-throughput enhanced matrix removal followed with UHPLC-QqQ-MS/MS for analysis of raspberry ketone-related phenolic compounds in adipose tissues

<br>

**See [original article](https://www.sciencedirect.com/science/article/abs/pii/S0039914021006378?via%3Dihub) published in _Talanta_.**

<br>

![](https://ars.els-cdn.com/content/image/1-s2.0-S0039914021006378-ga1.jpg)

<br>

## Abstract
Raspberry ketone (RK) is a major flavor compound in red raspberries, and it has been marketed as a popular weight-loss dietary supplement with high potential in accumulating in fatty tissues. However, challenges in extracting and characterizing RK and its associated phenolic compounds in fatty tissues persist due to the complex matrix effect. In this work, we reported a high-throughput sample preparation method for RK and 25 related phenolic compounds in white adipose tissues using an improved micro-scale QuEChERS (quick, efficient, cheap, easy, rugged and safe) approach with enhanced matrix removal (EMR)-lipid cleanup in 96-well plates, followed by UHPLC-QqQ-MS/MS analysis. The absolute recovery was 73–105% at the extraction step, and achieved 71–96% at the EMR cleanup step. The EMR cleanup removed around 66% of total lipids in the acetonitrile extract as profiled by UHPLC-QTOF-MS/MS. The innovative introduction of a reversed-phase C18 sorbent into the extract significantly improved the analytes’ recovery during SpeedVac drying. The final accuracy achieved 80–120% for most analytes. Overall, this newly developed and validated method could serve as a powerful tool for analyzing RK and related phenolic compounds in fatty tissues.
## Reference of Script
Data analysis was performed in R, and the script and output can be accessed [here](https://yuanbofaith.github.io/RK_adipose_QuEChERS_EMR). 

The R code has been developed with reference to [**R for Data Science (2e)**](https://r4ds.hadley.nz/), and the official documentation of [**tidyverse**](https://www.tidyverse.org/), and [**DataBrewer.co**](https://www.databrewer.co/). See breakdown of modules below:

- **Data visualization** with **ggplot2** ([**tutorial**](https://www.databrewer.co/R/visualization/introduction) of the fundamentals; and [**data viz. gallery**](https://www.databrewer.co/R/gallery)).

- [**Data wrangling**](https://www.databrewer.co/R/data-wrangling) with the following packages:
[**tidyr**](https://www.databrewer.co/R/data-wrangling/tidyr/introduction): transform (e.g., pivoting) the dataset into tidy structure; [**dplyr**](https://www.databrewer.co/R/data-wrangling/dplyr/0-introduction): the basic tools to work with data frames; [**stringr**](https://www.databrewer.co/R/data-wrangling/stringr/0-introduction): work with strings; [**regular expression**](https://www.databrewer.co/R/data-wrangling/regular-expression/0-introduction): search and match a string pattern; [**purrr**](https://www.databrewer.co/R/data-wrangling/purrr/introduction): functional programming (e.g., iterating functions across elements of columns); and [**tibble**](https://www.databrewer.co/R/data-wrangling/tibble/introduction): work with data frames in the modern tibble structure.





