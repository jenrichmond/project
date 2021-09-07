# project code club

The goal of Psych Code Club is to learn about data wrangling and visualisation in R via Tidy Tuesday. 

You can get the Tidy Tuesday data from the [github repo](https://github.com/rfordatascience/tidytuesday) here. The [tidytuesdayR package](https://github.com/thebioengineer/tidytuesdayR) makes it easy to read data into R. 


## Option 1 

Load the tidytuesdayR package and make a new .Rmd document.  Use the tt_load() function to read in the data. 

```
# load the package

library(tidytuesdayR)

# read in data by date
tt <- tt_load("2021-09-07")

# or year and week

tt <- tt_load(2021, week = 37)

```

## Option 2

Load the tidytuesdayR package and use the `use_tidytemplate()` function in the console to generate a template to work in. 

```

library(tidytuesdayR)

use_tidytemplate()

```


