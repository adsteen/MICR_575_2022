Homework 1 example
================

# Example Quarto document

## Markdown text features

This is an example of a Quarto document, like what you should produce
for Homework 1.

I would like you to have some plain text (like this), and to show that
you can use some of the markdown features. For instance, markdown makes
it easy to *italicize text*, make **boldface** text, and make headings
and subheadings. It also makes numbered lists very easy:

1.  First item
2.  Second item
3.  Third item

Your document should have of those things: headings, subheadings,
italicized and boldface text, and a bulleted or numbered list.

## Code

Your document should also have some R code that has executed properly,
like below.

``` r
1 + 1
```

    [1] 2

``` r
system.time({
  Sys.sleep(10)
})
```

       user  system elapsed 
      0.000   0.000  10.001 

For this assignment, you don’t need to do anything fancy with your code.
However, I’m feeling saucy, so I decided to put a plot into my quarto
document:

``` r
library(tidyverse) # loads the packages we need 
```

``` r
p <- ggplot(mtcars, aes(x=mpg, y=disp)) +
  geom_point()
print(p)
```

![](HMK_1_example_files/figure-gfm/unnamed-chunk-6-1.png)
