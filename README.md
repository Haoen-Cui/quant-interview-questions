[![Travis-CI Build Status](https://travis-ci.org/Haoen-Cui/quant-interview-questions.svg?branch=master)](https://travis-ci.org/Haoen-Cui/quant-interview-questions)

# Quantitatively Interviewed [Blog](https://haoen-cui.github.io/quant-interview-questions/)

This is the repo for the `Quantitatively Interviewed` blog. Please read the [About](https://haoen-cui.github.io/quant-interview-questions/about/) page of the blog for more info. 

# Development Logs 

This section serves as notes for myself or anyone who wants to reproduce this site. 

- `themes/beautifulhugo` was installed via `R` command 
`blogdown::install_theme(theme = "halogenica/beautifulhugo")`
- `themes/beautifulhugo/layouts/partials/footer_custom.html` was modified to include `MathJax` according to [section 2.5 of the `blogdown` book](https://bookdown.org/yihui/blogdown/templates.html). 
- `config.toml` URL configurations: I still haven't fully figure this part out. For details, see [Hugo configuration doc](https://gohugo.io/getting-started/configuration/). I think the relevant params are `baseurl`, `relativeURLs`, `conanifyURLs`, and `uglyURLs`. 
