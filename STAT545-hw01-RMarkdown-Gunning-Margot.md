Homework R Markdown
================
Margot Gunning

This is my Homework R Markdown file
===================================

-   It's so much fun.
-   This would have been super helpful for my Honours Thesis.
-   *Fact the first*: ctrl+alt+i = insert code chunk
-   *Fact the second*: can change the figure height/width in the chunk header section
-   *Fact the third*: this was copied from the STAT545a class repo

### Section One:

Walking through tutorial in class Sept 14/2017

``` r
fun_seq <- rnorm(100,100,2)
fun_seq2 <- rnorm(100,200,2)
plot(fun_seq, fun_seq2)
```

![](STAT545-hw01-RMarkdown-Gunning-Margot_files/figure-markdown_github-ascii_identifiers/chunk%20the%20first-1.png)

``` r
summary (fun_seq)
```

    ##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
    ##   96.15   98.99  100.15  100.37  101.74  105.64

``` r
summary (fun_seq2)
```

    ##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
    ##   195.5   199.0   200.2   200.3   201.8   205.3

### Section Two:

This fun graph was inspired by InstaChaaz

I suggest you take a look at his profile for some laughs:

(<https://www.instagram.com/instachaaz/>)

``` r
x <- log(seq(1,20,1))
y <- seq(1,20,1)
plot(x,y, 
     type = "l", 
     col = "red",
     xlab = "Instances of profanity screamed across the open office plan", 
     ylab = "Lenght of time I spend continously coding (hr)", 
     main = "Lab life", 
     yaxt='n', 
     xaxt='n')
```

![](STAT545-hw01-RMarkdown-Gunning-Margot_files/figure-markdown_github-ascii_identifiers/chunk%20the%20third-1.png)
