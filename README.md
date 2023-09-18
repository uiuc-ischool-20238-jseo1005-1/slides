# Slides for IS 407

## Course Slide Decks

- [week1-01-welcome](week1-01-welcome).

- [week2-01-data-viz](week2-01-data-viz).

- [week2-02-viz-num-cat](week2-02-viz-num-cat).

- [week4-01-tidy+wrangle](week4-01-tidy+wrangle).

- [week5-01-Fdf-join](week5-01-df-join).

- [week5-02-tidying](week5-02-tidying).

<!--

- [week4-02-data-type+class](week4-02-data-type+class).

- [week5-01-data-import+recode](week5-01-data-import+recode).

- [week6-02-web-scrape](week6-02-web-scrape).

- [week7-01-effective-dataviz](week7-01-effective-dataviz).

- [week7-02-functions+iteration](week7-02-functions+iteration).

- [week8-01-studies-confounding](week8-01-studies-confounding).

- [week8-02-regex](week8-02-regex).

- [week10-01-language-of-models](week10-01-language-of-models).

- [week10-02-modeling-nonlinear-relationships](week10-02-modeling-nonlinear-relationships).

- [week11-01-model-multiple-predictors](week11-01-model-multiple-predictors).

- [week11-02-logistic-reg+feature_eng](week11-02-logistic-reg+feature_eng).

- [week12-02-text-analysis_tf](week12-01-text-analysis_tf).

- [week13-01-accessible-viz](week13-01-accessible-viz).

- [week14-01-text-analysis_tfidf+sentimentanal](week14-01-text-analysis_tfidf+sentimentanal)

- [week14-02-shiny-practice](week14-02-shiny-practice)

- [week13-02-named_entity_recognition](week13-02-named_entity_recognition). -->

## Dev Toolkit Notes

Slides are built in using the **xaringan** package. See [here](https://github.com/yihui/xaringan) for more info on xaringan. There are two main reasons for choosing this format:

1. `xaringan` slides are R Markdown based, meaning code, output, and narrative can all live in one place and compiling the slides will run the R code as well.
2. Slide output is mobile friendly.

### Dev Instructions

Each slide deck is in its own folder, and one level above there is a custom css file. To compile the slides use `xaringan::inf_mr(cast_from = "..")`. This will launch the slides in the Viewer, and it will get updated as you edit and save your work.

## Acknowledgements

This course and materials are supported by and highly indebted to Mine Centinkaya-Rundel and Posit Education Team.
