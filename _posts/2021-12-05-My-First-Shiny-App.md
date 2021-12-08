
MY first Shiny App explores the demographics of food security in the
United States as a whole. It sources data from the “December 2020 Food
Security Supplement” from the United States Census Bureau. Users can
explore numerical and graphical summaries of food security, fit
prediction models, and view/download filtered subsets of the data.

[2020 Food Security Shiny
App](https://not-that-john-williams.shinyapps.io/food-security-shiny-app/)

[Source
Code](https://github.com/not-that-john-williams/food-security-shiny-app)

## Code Used to Generate This Blog Post

``` r
rmarkdown::render("_Rmd/2021-12-05-My-First-Shiny-App.Rmd", 
                  output_format = "github_document", 
                  output_dir = "_posts", 
                  output_file = "2021-12-05-My-First-Shiny-App.md")
```