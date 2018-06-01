---
title: "Introduction to Implementing an Exercise"
teaching: 30
exercises: 10
questions:
- "How do you write an exercise?"
objectives:
- "Know how to write an exercise"
keypoints:
- "Exercise are written in side a `>` - block."
---

~~~
hello carpentry instructors!
~~~
{: .output}

~~~
print("hello carpentry instructors!")
~~~
{: .language-python}

~~~
x <- 4
~~~
{: .language-r}

~~~
x <- c(4,)
~~~
{: .language-r}

~~~
Missing element after comma
~~~
{: .error}

Thisis crown down.

This is our first exercise

> ## What is required as an exercise
>
> List of the elements that you need inside an exercise
> to comply with the Carpentries style.
>
> > ## Solution
> > Exercise  are inisde a `>` - block and each block must have:
> >
> > - a title
> > - exercise body
> > - solution to exercise
> {: .solution}
{: .challenge}

You can use code blocks inside exercises.

> ## How to use R code in R-markdown
>
> Provide an exame that is to be run by R Markdown.
> 
>
> > ## Solution
> > Exercise  are inisde a `>` - block and each block must have:
> >
> > ```{r}
> > x <- 1
> > 1 -> y
> > x + y
> > ```
> {: .solution}
{: .challenge}
