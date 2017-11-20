# CHILDES_Lexical-diversity
This project explores children's lexical diversity and its relation with maternal vocabulary diversity, based on [CHILDES corpus](http://childes.talkbank.org)

## Context/Background
- Lexical diversity of children, as one crucial component of language skills, have been investigated in abundant research. It affords the potential for communicating, socializing and learning new skills. In addition, vocabulary diversity of maternal language is found to strongly relate to children's language skills and cognitive development. 
 - The index of lexical diversity employed in this project is [MTLD] (https://www.ncbi.nlm.nih.gov/pubmed/20479170) method. A concise comparison between MTLD and vocd-D (Malvern and Richards, 1997) also offered in [CHILDES_Lexical-diversity](https://github.com/yawenyu93/CHILDES_Lexical-diversity/blob/master/CHILDES_Lexical-diversity.Rmd).

## Install essential R packages
1.`childesr` package
The [childesr](https://github.com/langcog/childesr) package allows us to access data from [CHILDES corpus](http://childes.talkbank.org) with great convenience. 

 - install `childesr` package from GitHub repository
```
install.packages("devtools")
devtools::install_github("langcog/childesr")
```

2. `koRpus' package
The [koRpus] (https://cran.r-project.org/web/packages/koRpus/index.html) package provides handy tools to analyze text, including multiple indices of lexical diversity (e.g. type token ratio, HD-D/vocd-D, MTLD). 


