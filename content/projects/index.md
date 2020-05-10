---
title: "Projects"
draft: false
---

## Transfer Tutor
---

> A small prototype web [app](http://167.71.94.110:3000) that I built using JS to study the usefulness of teaching R from the perspective of Python. Participants found that relating R to their more familiar Python language was useful and they found the incremental stepping through the code helpful. **Note:** *You can skip all screens with google forms, which were used for the study itself.*

## py2r
---

> An interactive [lesson](https://nshrest.shinyapps.io/py2r_transfer/) using [learnr](https://rstudio.github.io/learnr/index.html) which can be used to teach Python programmers the basics of dataframe manipulation in R (base or tidyverse). The tutorial is different from others because it provides interactivity via code exercises to reinforce facts about R and relates to Python code / output using [reticulate](https://rstudio.github.io/reticulate/). The tutorial also points out "gotchas" when making the transition, as well as pointing out the advantages of tidyverse (`dplyr`). [[Source](https://github.com/nischalshrestha/py2r)]

## Automatic WAT Discovery
---

> This is an ongoing [project](https://github.com/nischalshrestha/automatic_wat_discovery) to automatically discover code behavior inconsistencies ([WATs](https://www.destroyallsoftware.com/talks/wat)) between Python and R using corpus from Kaggle. The project makes use of [rpy2](https://rpy2.bitbucket.io) to parse through simple one-liner snippets across the Python and R notebooks. Once parsed, the snippets for each language are executed against generated or provided data. Finally, dataframe outputs are compared between Python and R snippets, using basic metrics like row/column dimensions, cell values and syntactic edit distance. 

