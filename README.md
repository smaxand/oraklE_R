# oraklE_R

R package for Long-term Electricity Demand Forecasting

Installing the development version:

```library(devtools)```

```install_github("Autarky-Power/oraklE_R")```

Install requirements:
```packages <- c("caret","countrycode","doParallel","dplyr","ggplot2","ggthemes","glmnet","httr",
              "jsonlite","lubridate","MLmetrics","MuMIn","parallel","patchwork","purrr","R.utils",
              "readxl", "xml2")```

```install.packages(setdiff(packages, rownames(installed.packages())))```


[![Github All Releases](https://img.shields.io/github/downloads/Autarky-Power/orakle/total.svg)]()

## Flowchart for package use

The functions included in the package can be used separately or combined in the function full_forecast()

<img src="https://github.com/Autarky-Power/oraklE_R/assets/45041403/c166e930-876a-4e90-873a-3f4bcda249a7)https://github.com/Autarky-Power/oraklE_R/assets/45041403/c166e930-876a-4e90-873a-3f4bcda249a7" width="600">
