# Meetings with Mar 

## 20241218 - December 18th, 2024

- add Ray meta-analysis to zotero
- create a new Rmd document to create a pdf
- In Rmd, write up a few summary sentences of ray et al paper
- work through the [zotero_and_R](https://github.com/MarschmiLab/Lab_Protocols/tree/main/Computing/Project_Organization/zotero_and_R) documents on the lab github to learn how to integrate zotero and R for a bibliography with the Ray et al paper
- attempt to make pdf document with Rmd

Example YAML header for Rmd file for pdf conversion: 

```
---
editor_options: 
  chunk_output_type: console
bibliography: references.json
output:
  bookdown::pdf_document2:
    latex_engine: xelatex
    toc: false
geometry: margin=1in
papersize: a4
pagestyle: empty
fontsize: 12 pt 
---
```


## 20241211 - December 12th, 2024 

Goals for the week: 

- Getting set up in the lab Git Hub.
- name lab notebook -> "MillerK_LabNotebook_24-25" done
- Create local repository  done
- Continue working through RStudio. 

Other to-dos:

- Download Zotero  done
