stackrdown
=============

Output formats for stack.js HTML presentations for Rmarkdown. See it in action here <http://sachsmc.github.io/stackrdown>. 

## Installation

```r
devtools::install_github("stackrdown", "sachsmc")
```

## Usage

When authoring a document in rmarkdown, simply specify the output format in the front-matter:

```
output: 
    stackrdown::stack_presentation:
      theme: light
```

New slides are created with level 1 or level 2 headings. Specify light or dark for black on white, or white on black, respectively. 
