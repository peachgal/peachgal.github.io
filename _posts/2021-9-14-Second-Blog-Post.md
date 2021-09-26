Programming Background
================
Jasmine Wang
9/14/2021

## My thoughts on R vs other softwares

### Everyone in this course had some programming experience coming in (due to the prerequisites). What are your thoughts on R vs whatever other software you’ve used?

I think R is a great, open-source software for data analysis if the data
you are dealing with is not big data. Being an open-source software R
is, has its pros and cons. Pros are since it is open-source, there are a
lot of packages people developed to accomplish different needs in data
analysis. However, cons are we cannot trust the results from those
packages when they are not verified. When the packages are not verified,
their results can be misleading in data interpretation and hence cause
other problems.

R definitely has its strengths and its weaknesses. For example, plotting
tools are not easy to use. Some people prefer the easier Tableau to
plot, and I have to agree with them, too. Tableau is far superior to use
and well-known for its graphical ability. Just imagine if we have to
code all that plotting in R. It would be a chaos for me and
time-consuming as well.

### What functionality do you like about R?

I definitely like R being a free, open-source software with tons of
packages people developed over the years. Once those packages are
verified and the outputs are correct, they are great add-on tools of R.
There are a ton of packages people developed for different types of data
analysis such as time-series, spatial data, and spatial-temporal data.
In addition, the basic package comes with R is also great and easy to
use.

R is considered an advanced programming language like SAS, and hence, it
has a lot of things running in the background already to help people
code. R automates a lot of things in the background so that its users
can spend more time on data analysis, less time on data preparation and
extraction. Therefore, once you learn its syntax, it is very easy to
code, and its syntax is not hard, either.

### What parts do you miss about your other language?

I think the biggest drawback about R is its speed. For example, it is
impossible to run big spatial data in R. When a data analysis requires a
lot of memory to run due to its massive data size, it would take R hours
to run it but only minutes by other non-advanced programming languages
like Python. Thus, with medium-sized data set not required too much
memory to run, R is great. However, when the data is huge and requires
big memory to run them, a non-advanced programming language like Python
is usually preferred.

Generally speaking, the run time in R is slower than most of the
non-advanced programming languages. For instance, a simple example of
looping a 300 by 300 square matrix with if or else conditions may take R
minutes to run but only seconds in Python. Hence, speed is what I miss
about Python.

### Do you consider R a difficult language to learn? (If you knew R prior to the course, describe your experience when first learning it.)

No, I do not think R a difficult language to learn, as least not as hard
as Python. However, some people with Computer Science background may be
very comfortable with programming languages like Python, C++ and Java.

I first learnt R in prior Statistical courses to manipulate data and
cleanse data and prepare data for further analysis. I was mostly
confused about rows and columns. I was not sure about the orders of rows
and columns in a data set to extract certain information, and if there
were lists involved, it would just confuse me further. Luckily, with
enough R code examples from class notes and online resources, I was able
to gain control of R and complete the tasks given. From my experience,
comparing to Python, R was easy to learn. Python, on the other hand, was
a bit harder to grasp. However, I think many people have said this
already. For any programming languages, when you learn how their syntax
and logic work, especially in today’s world, with tons and tons of
resources and tutorials online, Spend a little time on learning the
language, you will be rewarded with sweet knowledge.

## R Markdown ouput to a plot

Below is an example of scatter plots of `iris` data set with 5
variables, Sepal.Length, Sepal.Width, Petal.Length, Petal.Width,
Species.

![](../images/iris-1.png)<!-- -->

Below is the **render function** I used to run in the console to produce
the R markdown blog post in github.

``` r
rmarkdown::render("C:/Users/peach/Documents/ST558/ST558_repos/peachgal.github.io/_Rmd/2021-9-14-Second-Blog-Post.Rmd", output_format = "github_document", 
                  output_dir = "C:/Users/peach/documents/ST558/ST558_repos/peachgal.github.io/_posts", 
                  output_options = list(html_preview = FALSE)
                  )
```
