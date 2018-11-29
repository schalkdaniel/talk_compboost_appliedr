# compboost

Component-wise boosting applies the boosting framework to statistical models, e.g., general additive models using component-wise smoothing splines. Boosting these kinds of models maintains interpretability and enables unbiased model selection in high dimensional feature spaces.
The R package compboost is an implementation of component-wise boosting written in C++ to obtain high runtime performance and full memory control. The main idea is to provide a modular class system which can be extended without editing the source code.

-   Presentation: https://danielschalk.com/talk_compboost_appliedr/ 
-   Source code: https://github.com/schalkdaniel/compboost

## Credits

This template highly depends on the great work others have already done:

- [**revealjs**](https://revealjs.com/)
- [**Font-Awesome:**](https://www.google.com)
- [**rmarkdown**](https://rmarkdown.rstudio.com/)
- [**revealjs (R Package)**](https://cran.r-project.org/web/packages/revealjs/index.html)
- [**Google Fonts**](https://fonts.google.com/)

## Extract PDF 

You can extract the pdf with decktape and docker:

```
sudo docker run --rm -t -v `pwd`:/slides astefanutti/decktape reveal https://danielschalk.com/talk_compboost_appliedr/#/ slides.pdf
```