## Multiverse Reports with RMarkdown's Dynamic Code Chunk Creation and Tabbed Interface

![](https://raw.githubusercontent.com/r-pkg-examples/rmarkdown-multiverse-dynamic-code-chunks-and-tabs/blob/main/multiverse-demo.gif)

> **multiverse:** a theoretical reality that includes a possibly infinite number of parallel universes.
> 
> --- [Webster's Dictionary](https://www.merriam-webster.com/dictionary/multiverse)

Within this repository, we experiment with two `rmarkdown` features to access a ["multiverse"](https://en.wikipedia.org/wiki/Multiverse) for exploration on data. In particular, we are leveraging:

- [RMarkdown Cookbook - 14.7: Use `knitr::knit_expand()` to generate Rmd source](https://bookdown.org/yihui/rmarkdown-cookbook/knit-expand.html)
- [RMarkdown Cookbook - 17.6: Put content in tabs](https://bookdown.org/yihui/rmarkdown-cookbook/html-tabs.html)

In this example, we are combining results from two distinct hyper-parameters (`K`, `O`) used to fit a model and examine their underlying results.
Under this structure, we can flip back-and-forth between choices without great difficulty. 

## Motivation

We have recently been considering ways to examine results across multiple models and scenarios within a single report. 
Previously, we created separate reports for specific clusters of simulation conditions.
However, when we went to compare raw results and graphs, we were constantly switching between web browser tabs and 
had to always make sure to open the tabs in a pre-specified order. 
When [Marvel's "What If"](https://en.wikipedia.org/wiki/What_If...%3F_(TV_series)) began to air on [Disney+](https://www.disneyplus.com),
we were inspired to look more deeply at the result comparisons. 

## License

GPL (\>= 2)
