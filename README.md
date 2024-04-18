# AlberdiLab code repository

This is the source code of the entry page to the AlberdiLab code repository. To access the HTML (website) version visit: 

- [alberdilab.github.io](alberdilab.github.io).

```{r}
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```
