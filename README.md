
# Advanced Research Methods foR Psychologists

This Github repo contains all lesson files used in the *Advanced
Research Methods foR Psychologists - Practical Applications in R*,
taught at Ben-Gurion University on the Negev (2019-2020). These lessons
cover the basics of R, basic frequentist and Bayesian testing, and the
basics of linear regression modeling (moderation, prediction, model
comparison, etc…).

**Notes:**

  - Please note that some code does not work *on purpose*, to force
    students to learn to debug. <sub>(Other code might not work because…
    I’m only human, okay??)</sub>  
  - Solutions to exercises are not provided here (yet?). Sorry.

## List of packages

Here is a list of packages used in the course, by lesson:

``` r
pkgs <- c(
  # 02 data.frames
  "tidyverse", # "reader", "dplyr", "tidyr",
  # 03 misc1
  "Hmisc", "mice", "dplyr", "tidyr", 
  # 04 describing data
  "dplyr", "psych", "ggplot2",
  # 05 testing
  "psych", "apa", "ppcor", "BayesFactor", 
  # 06 regression
  "dplyr", "parameters", "performance", "psych", "see",
  # 07 hierarchical (and dummy)
  "dplyr", "emmeans", "car", "performance",
  # 08 moderation
  "dplyr", "emmeans", "interactions",
  # 09 mediation & curvilinear,
  "ggplot2", "performance", "emmeans", "JSmediation",
  # 10 beyond NHST
   "BayesFactor", "bayestestR", "see",
  # 11 misc2
  "performance", "dplyr", "ggplot2", "GGally", "ggResidpanel"
)
```

You can install all the packages used by running:

    pkgs <- c(
      "apa", "BayesFactor", "bayestestR", "car", "dplyr", "emmeans",
      "GGally", "ggplot2", "ggResidpanel", "Hmisc", "interactions",
      "JSmediation", "mice", "parameters", "performance", "ppcor",
      "psych", "see", "tidyr", "tidyverse"
    )

``` r
install.packages(pkgs, dependencies = TRUE)
```

### To Do

  - [ ] Equivalence testing(?)
  - [ ] Logistic Regression
