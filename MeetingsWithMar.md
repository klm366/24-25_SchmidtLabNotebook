# Meetings with Mar 

## 20250319
**Kelly's Game Plan:**
- Thursday: look for/read papers on qPCR of denitrification genes (*nirS* (+*K*), *nosZ*, maybe *nor*). Develop a conceptual understanding of qPCR
- Tuesday (3/25): build phylogenetic tree with oyster dataset based on phylo tree learnings from Wed 3/19 lab.
- Wednesday (3/26): lab and lecture!

**Long-term:** investigate the beta diversity of oyster sediment microbial communities and quantify their various denitrification genes to get an idea of nitrous oxide emissions from oyster bed microbial denitrification.

## 20250313 - March 13th, 2025
- Mar will repeat the DADA2 workflow for the New England oyster microbiota project; Kelly will analyze the data, using the Paliy and Shankar paper on multivariate statistics as a guide
- Kelly will watch the lecture happening next Monday (and finally turn in her lit review!!)
- long-term plan for Kelly - beta analysis, qPCR
- symposium dates: May 20th and 21st

## 20250225 - February 26th, 2025
- finishing rough draft of lit review by Thursday and sending to Mar to look at
- learning PCR from Sophia Thurs, next Tues
- re-reading Feinman paper for discussion with Mar in our meeting next Tues :)

## 20250212 - February 12th, 2025

To-Dos for Kelly:
- Pomodoro Technique the hell out of the two theme sections of my lit review
- start committing a PDF along with the Rmd file when I push to GitHub
- learn how to log on to BioHPC server

Things I would like help with from Mar:
- How to text wrap in Rmd
- Would love a look-over of the content in my intro
- Audio record future lectures?

Future participation in BIOMI 4300/6300:
- Mar will share the slides and audio-record lectures, if possible
- Kelly will attend discussions on Wednesday mornings and is welcome to go to the lab component of the class, when she has time and feels ready to dive in a little more

## 20250204 - February 4th, 2025

Discussion of the literature review due on February 15th 

- Intro: 
	- Role of microbes in marine environments (both in water and sediments), nitrogen and microbial loop
		- Microbial interdependence
		- Ecosystem Health/ water quality 
	- Oysters, history of population depleted, farming
		- promote ecosystem health/water quality by changing microbes/nitrogen cycle
- Theme 1: Oysters enhance marine bnethic microbial biodversity and modify microbial composition. 
	- Microbial compositional change? V4 16S rRNA sequencing methods 
	- Within sample (alpha) diversity: richness and evenness
	- Between-sample diversity: Abundance-unweighted and -weighted dissimilarity (Sorensen/Bray-Curtis and UniFrac)
		- **Who** drives the difference (via differential abundance)? Which taxa change because of oysters
- Theme 2: Oysters promote marine benthic microbial denitrification.
	- Who changes in controls versus oyster sediments? Do they carry genes related to denitrification? 
	- Functionl/metabolic changes due to oysters
		- Microbial studies (that include quantitative PCR (qPCR), functional annotation of 16S rRNA genes with FAPROTAX or PICRUSt2)
		- Biogeochemistry studies (including isotope tracers, nitrogen flux measurements, models)



## 20250107 - January 7th, 2025

- help/attend the Carpentries workshop Jan 14-15. :) Enjoy the process and assist learners. :)  
- Continue to read papers on oysters
	- Check out papers that Mar posted in GitHub in the `relevant_papers` folder. 
		1. Feinman et al., 2018 - The Influence of Oyster Farming on Sediment Bacterial Communities
		2. Stevens et al., 2024 - Oyster aquaculture enhances sediment microbial diversity- insights from a multi-omics study
		3. Murphy et al., 2019 - Bioreactivity and Microbiome of Biodeposits from Filter-Feeding Bivalves 
- As you read papers take notes on their main points. 
- Add to the literature review document as you read, thinking of ways that you can combine concepts from each paper. 



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
