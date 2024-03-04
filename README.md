# serghioutemplates

<div align="justify">
 
An R Markdown template that combines all templates I use and all of my pre-defined code to avoid copy-pasting. Excited to hear any ideas/feedback about what could be done better! 

Please reference the repository if you happen to use it :)

## Quarto

Even though I currently prefer quarto files, the templates functionality is still not available in RStudio (even though this is possible). As such, for the time being, this package still generates RMarkdown files. Simply take the RMarkdown file and save it as a .qmd to get a Quarto file.

## Install

```r
devtools::install_github("serghiou/serghioutemplates")
```

This is not a fully  blown package yet, so you'll have to manually install some basic dependencies using the code below.

```r
packages <- c("prettydoc", "tufte", "rmdformats", "epuRate")
install.packages(packages)
```


## Use

```r
library(serghioutemplates)
```

## Customize

If you fork this repo (top right-hand corner), you can change the original template however you please to create your own template with your own preferences. Ideally, this would be part of the package, but at the moment there is no bandwidth to work on this.


## Other

You may enjoy a list of my favorite resources and packages for R [here](serghiou/best-of-r) (feel free to recommend packages that you do not see, but you strongly feel that you should!).


## Acknowledgements

This package would have not been possible without the great work of the community that went through the effort of creating the packages on which this meta-template depends and their dedication to open source.

</div>
