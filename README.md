# MBZUAI Single Cell Biology and Bioinformatics Courses

This repository collects the course materials for two computational biology courses being taught by [Prof. Eduardo Beltrame](https://mbzuai.ac.ae/study/faculty/eduardo-beltrame/) at [MBZUAI](https://mbzuai.ac.ae) in Spring 2025:

- **CB703**: Introduction to Single Cell Biology and Bioinformatics
- **CB803**: Single Cell Biology and Bioinformatics

Lectures are on Mondays and Wednesdays 6:30PM UAE time, and labs Thursdays 10:30AM UAE time. 

Both courses have a shared set of lectures, and different labs and evaluations. The lectures are open for online auditing, please reach out to eduardo.beltrame@mbzuai.ac.ae if you'd like to audit. The materials for the labs will be made available in this repository, but labs cannot be audited online (if you are at MBZUAI and we have space you may audit the labs in person). 

## Piazza Forum and Zulip chat

For the Spring 2025 edition of the course we use Piazza for student discussion and announcements. 
Please try to using Piazza instead of email for questions whenever possible. This way your colleagues learn from your questions and may also help you answering them. Piazza will also be very useful for the project discussion and development. To join our Piazza Forum use the access code `scbb` and the sign up link here: [https://piazza.com/mbzuai.ac.ae/spring2025/mbzuaicb703cb803](https://piazza.com/mbzuai.ac.ae/spring2025/mbzuaicb703cb803)

Aditionally, for chat conversations, we have created a channel in the scverse Zulip. scverse is the community of computational for single cell omics, which we will be utilizing for this class. Zulip is an online chat community similar to discourse and Slack, to which you can sign up using your email or GitHub account. Chats are visible to all members of the community that are signed in. This is a great opportunity to not only discuss with your class mates, but especially to be exposed to the [scverse.org](https://scverse.org/) community discussions. Join our class channel in the scverse Zulip here:

[https://scverse.zulipchat.com/#narrow/channel/476882-MBZUAI-Course---Single-Cell-Biology-and-Bioinformatics](https://scverse.zulipchat.com/#narrow/channel/476882-MBZUAI-Course---Single-Cell-Biology-and-Bioinformatics
)


## Course references and preparation
There is no textbook for single cell biology and bioinformatics. The materials for this course are necessarily a collection of miscellaneous resources, especially scientific articles and online resources. 

For the initial weeks, as we cover essential biology concepts, we will recommend reading a few initial chapters of the textbook [Essential Cell Biology](https://wwnorton.com/books/9781324033356), by Bruce Alberts et al. This book is especially important for readers that are unfamiliar with biology, and we recommend reading chapters 1, 2, 4, 5, 7 and 8. 

For the bioinformatics part of the course, we will focus on Python based tools. We will primarily work with the [scvi-tools](https://scvi-tools.org/) framework for probabilistic modelling for single cell omics, and with other tools that are part of the [scverse](https://scverse.org) ecosystem of Python based tools for single cell omics. It is important to be familiar with Python, GitHub, and using the command line. If you are unfamiliar with these or need some brushing up, we recommend the initial lectures of the [Caltech Bootcamp in Programming in the Biological Sciences](https://justinbois.github.io/bootcamp/2024/) by Justin Bois. 

Most of the labs and computational practices of this course will be done using Python Jupyter notebooks, and we are designing the to be doable within the Google Colab notebooks, available at: [https://colab.research.google.com](https://colab.research.google.com/#). **If you are not familiar with Google Colab, we strongly recommend that you spend a while becoming familiar with it. Start with this notebook [Overview of Google Colaboratory Features](https://colab.research.google.com/notebooks/basic_features_overview.ipynb). You can watch this [4-min video explaining the Google Colab integrated AI assistant](https://www.youtube.com/watch?v=V7RXyqFUR98) that is very helpful.**

 

## Evaluation (for enrolled students)
The evaluation for this course will be comprised of:
- (10%) Attendance/quizzes
- (35%) Problem sets (PS), may be solved in groups but turned in individually
- (10%) One take-home midterm exam (equivalent to a problem set, but must be solved alone)
- (15%) One midterm project to be done in groups of 2-4 people, to be presented on April 3
- (30%) One final project to be done in groups of 2-4 people (may be the same group as the midterm project, may expand on the same topic). To be presented on the weeks of April 21-30.

### [Midterm & Final project paper writing guidelines](https://docs.google.com/document/d/e/2PACX-1vRBBA4fd4UuGEskrSdr-FQRhXvQ8LSeSo_x1wPOGsAhSea4JcTVRcO9VCumMS0QZ7FMTk04_AS-KJlV/pub?embedded=true)

## Course schedule
The weekly course schedule is below. Please note that this is the first time this course is being taught, and there might be adjustements to the schedule, content and activities depending on course pace and opportunity to host guest speakers for some lectures.

The MBZUAI 2025 spring term runs from January 6 to April 30 (last day of classes, finals in May), with a spring break on the week of March 24-28. 

### Week 1: Fundamental concepts in biology, part I 
The central dogma of molecular biology. The building blocks of the cell: DNA, RNA, protein, sugars, lipids, small molecules.
- **Jan 6** - [Lecture 1.1 slides](https://www.canva.com/design/DAGa_5zCtmM/fF-XIz95hKu27fkXsNhA_w/view?utm_content=DAGa_5zCtmM&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h266f373449). Introduction & fundamental concepts
- **Jan 8** - [Lecture 1.2 slides](https://www.canva.com/design/DAGbJZIdru4/PcBN7aQNPI1upvQ_zwhJvA/view). The building blocks of the cell & the central dogma of molecular biology. 
- **Jan 9** - [Lab 1 activities](https://docs.google.com/document/d/e/2PACX-1vTeg-g3ItetECcGhzgj6SsduqoRhucW35Dkg4bZ5cbVozd9iI8RXrCR9XwWxaludJZ8Jw43Jgj4D2Ku/pub): Visualizing biology – molecular structures and the protein data bank
- _[Problem set 1: Fundamental Concepts in Biology](https://docs.google.com/document/d/e/2PACX-1vRHXvVIQd_kJMzYTfzP2DVyYrM4szCojlpThSO4ybtLRtAqwHBhQHBamvDDz2YxUuytBU21PFeavRW6/pub). Released on Jan 9. Due Jan 23._
  
#### Required Reading
- **(Lecture notes)** [A Conceptual Introduction to Single Cell RNA sequencing](https://github.com/Munfred/scbb/blob/main/introduction.pdf) 
- **(One-page article)** [The importance of stupidity in scientific research (PDF)](https://journals.biologists.com/jcs/article/121/11/1771/30038/The-importance-of-stupidity-in-scientific-research), by Martin A. Schwartz. J Cell Sci 1 June 2008; 121 (11): 1771. DOI: [https://doi.org/10.1242/jcs.033340](https://doi.org/10.1242/jcs.033340)
- **(7 video playlist, 12 min total)** [The central dogma of molecular biology](https://www.youtube.com/watch?v=SMtWvDbfHLo&list=PLCF1EBB5E07F55383)
- **(Online resource)** [Molecular Machinery: A Tour of the Protein Data Bank](https://cdn.rcsb.org/pdb101/molecular-machinery/)


#### Recommended reading:

- **(Book)** [Essential Cell Biology](https://www.slideshare.net/slideshow/essential-cell-biology-5th/256499286#18). 
Chapter 1 (Cells: The Fundamental Unit of Life) and Chapter 2 (Chemical Components of Cells)
- **(Book)** [The Machinery of Life](https://archive.org/details/machineryoflife0066good/page/n9/mode/2up) Chapter 1 (Introduction), Chapter 2 (Molecular Machines) and Chapter 4 (Protein Structure and Function)
- **(5 min video)** [Physically accurate computational modelling of the dynamics of DNA and chromatin.](https://www.youtube.com/watch?v=4Z4KwuUfh0A)

**Other interesting references**
- **(Book)** [The Blind Spot: Why Science Cannot Ignore Human Experience](https://mitpress.mit.edu/9780262553032/the-blind-spot/). By Adam Frank (astrophysicist), Marcelo Gleiser (theoreticla physicist), Evan Thompson (philosopher).
Publisher: The MIT Press (March 5, 2024)
- **(Verse)** [Tao Te Ching chapter 27](https://terebess.hu/english/tao/mitchell.html#Kap27), translated by Stephen Mitchell (1988)

### Week 2: Fundamental concepts in biology, part II 
**Note:** This week [Surya Narayanan Hari](https://www.canva.com/design/DAGb4iM5dzo/V1m8DzqCBNXqMAiXpUshzg/view?utm_content=DAGb4iM5dzo&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hf6449141cc) will be visiting from Caltech and may give a guest lecture on Jan 15.
- **Jan 13**- [Lecture 2.1](https://docs.google.com/document/d/e/2PACX-1vT3B2Pry-FVsZo_28-Pli47QeYycd_fBwyUMBeIAUcB3gfXUjSNMS5nRlmSTWCWQgvjRBHinmAj56on/pub): Measuring the cell: omics and sequencing
- **Jan 15** - [Lecture 2.2 slides](https://www.canva.com/design/DAGcLQ-gWiY/WyuONA24M8igRjfQYXfpjA/view?utm_content=DAGcLQ-gWiY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h4c140002b2) Measuring the cell: Microscopy. Lecture by Luiz, with mini guest lecture by Surya at the end.
- **Jan 16** - [Lab 2 activities](https://docs.google.com/document/d/e/2PACX-1vT3B2Pry-FVsZo_28-Pli47QeYycd_fBwyUMBeIAUcB3gfXUjSNMS5nRlmSTWCWQgvjRBHinmAj56on/pub): Visualizing biology - microscopy

#### Required reading:

- **(Book)** [Essential Cell Biology](https://www.slideshare.net/slideshow/essential-cell-biology-5th/256499286#18). 
Chapter 3 (From DNA to Protein: How Cells Read the Genome) and Chapter 4 (Protein Structure and Function)


#### Recommended reading:

- **(Book)** [Essential Cell Biology](https://www.slideshare.net/slideshow/essential-cell-biology-5th/256499286#18). 
Chapter 5 (DNA and Chromossomes), and Chapter 8 (Control of Gene Expression)
- **(Book)** [The Machinery of Life](https://archive.org/details/machineryoflife0066good/page/n9/mode/2up) Chapter 3 (The Processes of Living) and Chapter 4 (Molecules in Cells: _Escherichia coli_ )
  


### Week 3: Biological assays and data generation 

- **Jan 20** - [Lecture 3.1 slides](https://www.canva.com/design/DAGceoQCSNY/SSadSRKSP3u9rMdn5mCI2g/view?utm_content=DAGceoQCSNY&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h6b64977f1b): Transcriptomics & biomonitoring 
- **Jan 22** - [Lecture 3.2 slides](https://www.canva.com/design/DAGc0s3VBjU/aFxyEhv51ou-gwDfRp6oOg/view?utm_content=DAGc0s3VBjU&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h1ba25c6782): Transcriptomics analyses
- **Jan 23** - [Lab 3 script](https://docs.google.com/document/d/e/2PACX-1vQNP42W709NxCyevLc2E3THjF7K0m3m0Fcj3DcMpGH5c_BMYk8ZZGHQM8Ge-vwTrGT-Z1kyC9iwh8J3/pub?embedded=true): Bulk RNA-seq analysis with Biojupies, String and Cytoscape
- By Jan 23: PS2 released (and PS1 due). PS2 Due Feb 6.
- [Problem set 2: Transcriptomics & bulk RNA-seq analysis](https://docs.google.com/document/d/e/2PACX-1vRpvr9ytHVpfqyVX-iTs_f71BehHi4wQAjs5Zv5SxTqdRwJjNyobXyflN6Sa4ltLlc1rQ_zMgXJ_lBE/pub?embedded=true)


#### Required reading:
- **(Article)** [A Beginner’s Guide to Analysis of RNA Sequencing Data](/doi.org/10.1165/rcmb.2017-0430TR). Koch et al (2018). DOI: 10.1165/rcmb.2017-0430TR. This article covers all of the common analysis done with RNA-seq data, read it and do not worry if you do not understand everything. 
- **(Website)** [RNA-seqlopedia](https://rnaseq.uoregon.edu/): Great website detailing the workflow for RNA-seq

#### Recommended reading:

- **(Website)** [BioJupies](https://maayanlab.cloud/biojupies/): Automatically Generate RNA-seq Data Analysis Notebooks.
- **(Website)** [GEO: Gene Expression Omnibus](https://www.ncbi.nlm.nih.gov/geo/). The NIH genomics data repository.
- **(Website)** [The Human Phenotype Project](https://www.pheno.ai/)
- **(Documentation)** [The Human Phenotype Project knowledge base](https://knowledgebase.pheno.ai). It will be useful to get acquainted with the HPP TRE documentation for the coming weeks. 


**Other interesting references**

- **(News Article)** [‘Dark proteome’ survey reveals thousands of new human genes](https://www.science.org/content/article/dark-proteome-survey-reveals-thousands-new-human-genes), _Science, November 2024_
- **(News Article)** [Launch of world’s most significant protein study set to usher in new understanding for medicine
](https://www.ukbiobank.ac.uk/learn-more-about-uk-biobank/news/launch-of-world-s-most-significant-protein-study-set-to-usher-in-new-understanding-for-medicine), UK biobank, January 2025
    - (Related 2 min video) [Protein Biomarker Detection with Olink Proteomics](https://www.youtube.com/watch?v=_3R2jLaBhV8), describing Olink technology being used by the new UK Biobank protein study 
  
### Week 4: Biological data representation 
- **Jan 27** - [Lecture 4.1 slides](https://www.canva.com/design/DAGdSBmBQhw/cz6wwie444ngUwLa_EXNNA/view?utm_content=DAGdSBmBQhw&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h5de7c88b8b): Single cell RNA sequencing data, alignment workflows, processing steps  
- **Jan 29** - [Lecture 4.2 slides](https://www.canva.com/design/DAGdgjg3AM0/jvCGleYyvQhcDnwDNmFURQ/view?utm_content=DAGdgjg3AM0&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h27fee3c536): Processing single cell RNA sequencing data with [scvi-tools](https://scvi-tools)
- **Jan 30** - [Lab 4 activities](https://docs.google.com/document/d/e/2PACX-1vQ6eK7qLpoaSv9GdxQyb8QfFVk7JWZJhUCbhGvyXOWA_YMO9pGW3xVtud4uHEEkH5JqS3dG7m4caWBV/pub): Processing single cell RNA sequencing data with [scvi-tools](https://scvi-tools)
 

#### Required reading:
- **(10 min video)** [2017 Presentation by Romain Lopez on the scVI model](https://www.youtube.com/watch?v=NlpqwjQ91Sc)
- **(Nature News Feature Article, 4 pages)** [Is AI leading to a reproducibility crisis in science?](https://www.nature.com/articles/d41586-023-03817-6) ([PDF](https://github.com/user-attachments/files/18549658/Is.AI.leading.to.a.reproducibility.crisis.in.science.pdf))

- **(Nature News Feature Article)** [AI is complicating plagiarism. How should scientists respond?](https://www.nature.com/articles/d41586-024-02371-z)

#### Recommended reading:
- **(Nature Comment Article, 4 pages)** [Garbage in, garbage out- mitigating risks and maximizing benefits of AI in research](https://github.com/user-attachments/files/18549669/Garbage.in.garbage.out-.mitigating.risks.and.maximizing.benefits.of.AI.in.research.pdf)

- **(Nature Article Collection)** [Science and the new age of AI](https://www.nature.com/immersive/d41586-023-03017-2/index.html)

### Week 5: Overview of single cell omics technologies 
**Note:** This week [Justin Hong](https://www.justinhong.me/) will be visiting from Columbia University and may give a guest lecture on Feb 3/5. [Aly Azeem Khan](https://people.cs.uchicago.edu/~aakhan/) will be visiting from the University of Chicago on February 5.
- **Feb 3** - Lecture 5.1: Probabilistic modelling of single cell omics data with scvi-tools - Guest lecture by Justin Hong
- **Feb 5** - Lecture 5.2:  Guest lecture by Justin Hong (continued, if needed). Visit from Aly Azeem Khan. 
- **Feb 6** - [Lab 5 activities](https://docs.google.com/document/d/e/2PACX-1vT0SKxgZYug8wlzbKppC-RYpawQBzzb0I6lj9EijGIKcpSCRYBhdSrs0KybXFFiKLA5YeQ1loLNz-Fh/pub):  Method development with scvi-tools, creating new probabilistic models for single cell omics data 
- **[Problem set 3: Single cell omics, alignment and data pre-processing](https://docs.google.com/document/d/e/2PACX-1vR2UYOq1uETbcvkkvZlX068r_uoOWQEWZm6NO1aPdpe_DXCq7YInBU7Uq33entezy9vGsg9RUYNV9fn/pub?embedded=true)** PS3 Due Feb 27.

### Week 6: Single cell RNA sequencing data pre-processing | The Human Phenotype Project (HPP)
- **Feb 10** - Lecture 6.1: Finding single cell omics datasets, pre-processing workflows to generate the gene count matrix 
- **Feb 12** - Lecture 6.2: The Human Phenotype Project data deep dive, guest lecture by Alvaro Maria Cabrera Berobide (MBZUAI masters student working on the HPP).
- **Feb 13** - Lab 6: Using the HPP Trusted Research Environment. NOTE: The demo environment is only available between February 12-15.  **(Lab guide)** [Registering Pheno TRE demo environment.pdf](https://github.com/user-attachments/files/18764816/Registering.Pheno.TRE.env.pdf)
- [Further instructions for lab](https://mbzuaiac-my.sharepoint.com/:w:/g/personal/alvaro_berobide_mbzuai_ac_ae/EVPKMjvkZ8dCgOSkrDoPhpgBktX9bl7UdqzJzM_rb4EKNA?e=lxmGAn)
#### Required reading:
- **(HPP data catalogue)** [https://humanphenotypeproject.org/data-access](https://humanphenotypeproject.org/data-access)
- **(HPP knowledge base)** [https://knowledgebase.pheno.ai/](https://knowledgebase.pheno.ai/)
  
### Week 7: Differential expression and biological network analysis  
**Note:** This week [Valentine Svensson](https://nxn.se/) will give a lecture on differential expression on February 19 and prof. [Natasa Przulj](https://mbzuai.ac.ae/study/faculty/natasa-przulj/) will give a lecture on Feb 17. 
- **Feb 17** - [Lecture 7.1 slides](https://github.com/user-attachments/files/18850180/MBZUAI.Comp.Bio.Students.Feb.13.2025.pdf) Guest lecture by prof. Natasa Przulj on biological networks
- **Feb 19** - [Lecture 7.2 slides](https://github.com/user-attachments/files/18960270/250219.-.Differential.expression.pdf) Guest lecture by Valentine Svensson on differential expression.
- **Feb 20** - [Lab 7 activities](https://docs.google.com/document/d/e/2PACX-1vS0AocrnK113OGXEEOHH_RcLC5vm4FTBPpWkGfQl5nuNhxjZfUZPXHjnySSXMcH6VOkSslH2NkXhnND/pub): scRNAseq pre-processing pipelines: aligners and pseudoaligners
  
### Week 8: Single cell RNA sequencing data analysis
- **Feb 24** - Lecture 8.1: Practical biological analysis tips
- **Feb 26** - Lecture 8.2: Data visualization
- **Feb 27** - [Lab 8 activities](https://docs.google.com/document/d/e/2PACX-1vS85j7r9PuXYQe8Jm960LD6Rh0E_LykqCQS-DAq9gGb8zmGERUYya1cba_GJkTKKteYVvISDq_PKeiB/pub?embedded=true): Reproducing the analysis of a published paper + deploying cellxgene

#### Required reading:
- **(YouTube Sanbomics Channel tutorial)** [Python single cell DE analysis with Scanpy and PyDEseq2](https://www.youtube.com/watch?v=Ee0PQUwVH8Q)
- **(Twitter Thread)** [Lior Pachter on Seurat and Scanpy differences for single cell analysis](https://x.com/lpachter/status/1776280345098494025)

#### Recommended reading:
- **(Cell Press paper on memento)** [Method of moments framework for differential expression analysis of single-cell RNA sequencing data](https://www.cell.com/cell/fulltext/S0092-8674(24)01144-9) 
- **(BiorXiv preprint)** [The impact of package selection and versioning on single-cell RNA-seq analysis](https://www.biorxiv.org/content/10.1101/2024.04.04.588111v2)
- - **(Youtube Videos)** [Caltech short Lectures from Santiago Lombeyda on visualizing data](https://www.youtube.com/watch?v=P8E0bl0fnyY)


### Week 9: Single cell RNA sequencing data analysis workflows 
- **Mar 3** - Lecture 9.1: Open science and peer review - open peer review of project proposals 
- **Mar 5** - Lecture 9.2: Open science and peer review (with guest lecture by Aziz Khan) - open peer review of project proposals  
- **Mar 6** - Lab 9: Reproducing the analysis of a published paper  
 

### Week 10: Guest lecture by Greg Gibson & Spatial Transcriptomics 
Note: on March 10 prof. [Greg Gibson](https://scholar.google.com/citations?user=e4_ZXcwAAAAJ&hl=en) from Georgia Tech will give a lecture in our class.
- **Mar 10** - Lecture 10.1: Guest Lecture by Greg Gibson
- **Mar 12** - Lecture 10.2: Spatial transcriptomics gueset lecture by Wouter-Michiel Vierdag, scverse core team
- **Mar 13** - Lab 10: Spatial transcriptomics analysis practice
  

### Week 11: Midterm project presentations & discussion
- **Mar 17** - Lecture 11.1: Midterm project presentations
- **Mar 19** - Lecture 11.2: Midterm project presentations
- **Mar 20** - Lab 11: Midterm project presentations
- Midterm project proposals discussion this week. 

### Spring Break: March 24-28
### Eid Al Fitr Holiday: March 29-April 1

### Week 12: Foundation models & benchmarking
- **Apr 7** - Lecture 12.1: Guest Lecture by prof. Aziz Khan on [On the art of reprodicible research.pdf](https://github.com/user-attachments/files/19908113/On.the.art.of.reprodicible.research.pdf)


### Week 13: Foundation models & benchmarking
- **Apr 7** - Lecture 13.1: Discussion on Midterm submissions and Guest Lecture by Aziz Khan on data visualization 
- **Apr 9** - [Lecture 13.2 Slides]: Guest Lecture by Tala from NYUAD on Malaria single cell study (https://github.com/user-attachments/files/19742558/MBZUAI_GuestLecture_Shahin_09042025.pdf)
- **Apr 10** - Lab 13: Work on final projects 


### Week 14: Single cell biological analysis in practice
- **Apr 14** - Lecture 14.1: Final projects feedback & discussion 
- **Apr 16** - Lecture 14.2: Foundation models in biology & benchmarking: Open Problems in Single Cell Analysis  
- **Apr 17** - Lab 14: Work on final projects 


### Week 15: Final project presentations and discussion 
- **Apr 21** - Lecture 15.1: Final project presentations 
- **Apr 23** - Lecture 15.2: Final project presentations 
- **Apr 24** - Lab 14: Work on final projects 

### Week 1: Final project presentations and discussion 
- **Apr 28** - Lecture 16.1: Final project presentations 
- **Apr 30** - Lecture 16.2: Final project presentations 


