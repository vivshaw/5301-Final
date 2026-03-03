# DTSA 5301 Coursework

This repo contains my coursework for DTSA 5301.

## COVID Cases and Deaths (US and Global)

- [4301-Final-COVID.Rmd](./4301-Final-COVID.Rmd) contains my R Markdown file visualizing and modeling COVID cases and death rates, across the US and its states, as well as globally.
- [4301-Final-COVID.html](./4301-Final-COVID.html) contains the knitted output as a readable HTML file.

**Ensure you have [`tidyverse`](https://tidyverse.org/) installed before trying to knit!**

## NYPD Gun Violence Incidents

- [4301-Final-Shootings.Rmd](./4301-Final-Shootings.Rmd) contains my R Markdown file visualizing and modeling shooting rates in NYC by borough and over time.
- [4301-Final-Shootings.html](./4301-Final-Shootings.html) contains the knitted output of the same as an HTML file.

**If you try to knit this yourself, ensure you have all of [`tidyverse`](https://tidyverse.org/), [`tidymodels`](https://www.tidymodels.org/), [`sf`](https://r-spatial.github.io/sf/), and [`nycgeo`](https://nycgeo.mattherman.info/) installed!** The two geo packages can be kind of a pain to install on some platforms. If you have issues installing, you can remove the choropleth section and the doc should knit just fine with only `tidyverse` and `tidymodels`.