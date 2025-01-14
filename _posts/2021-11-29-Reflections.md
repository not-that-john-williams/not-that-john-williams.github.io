
### On Ethics

In August 2021, I wrote the blog post “What is a Data Scientist?” My
answer: statistician + software engineer + artist. But I left out
another key role. Data scientists also must be respected ethicists, and
a quick review of what can go wrong when data scientists are
irresponsible shows why. Personal information is unprotected or
published without permission. Stereotypes are reinforced in predictive
policing. Automated decision-making limits economic opportunities in
school admissions, job hiring, and loan approvals. Healthcare decisions
could be made incorrectly, compromising a person’s health and even their
life. And, most recently in the public discourse, democratic systems can
be undermined when data scientists use algorithms to sow mistrust and
discord on social media. All of these can be consequences when ethics is
not top-of-mind in a data scientist’s training and professional career.
That’s why, after some reflection, I felt obligated to add to my
definition of a data scientist–part statistician, part software
engineer, part artist, and part ethicist.

### On R,

I’ve used SAS and R during my education at North Carolina State
University. For me, R (and R Markdown specifically) is a much better
environment for generating reports, creating ad hoc plots/graphics, and
documenting the data science process. Doing the same in SAS is
cumbersome and inefficient—maybe I just don’t know how, but I can never
get the SAS output to look like I want. R lets me be creative. The
numerous open-source packages make R elegantly flexible for whatever
data science task I have. I can access databases and API’s, create
predictive models, and design interactive web applications. I have
several personal data science projects that I look forward to completing
using R. Going forward, I’ll be using R Markdown for note taking on data
science projects, using Git for version control, and sharing my insights
on my GitHub blog. One thing I hope to create soon is an R Markdown
notebook of my frequently “how-to” web searches for R, so I can commit
them to long-term memory. The more I can instantly recall R syntax or R
methods versus searching for them will make my programming more
efficient.

## Code Used to Generate This Blog Post

``` r
rmarkdown::render("_Rmd/2021-11-29-Reflections.Rmd", 
                  output_format = "github_document", 
                  output_dir = "_posts", 
                  output_file = "2021-11-29-Reflections.md")
```
