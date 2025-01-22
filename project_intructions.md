Hi everyone!

On Monday I got a few questions about the class midterm and final projects, which is great: it means you're thinking about it. I wanted to share a few more details on the project expectations. Please also read carefully the section on Finding project collaborators and forming a group. 

The content of this email is also available on Piazza and at the course GitHub page at: https://github.com/Munfred/scbb/blob/main/project_intructions.md 


On midterm and final projects, & flavours of final projects
Both midterm and final projects may be executed with the same group and on the same topic (e.g. with the same dataset). The midterm project expectation is that you'll be able to choose a biological system, biological question, and find the relevant data, and then choose and handle the correct tools for with the data of your choice. Your group will submit a report on the project, and make a short (<15 min) presentation on it. 

For the final project expectations will be higher, in terms of biological analysis: in addition to all of the above you will need to try to ask a biological question and to figure out how to answer it using the tools of your choice, and to interpret the results you got. Your group submit a detailed report on the project, and make a detailed (20-30 min) presentation on it. 

Here is a very didactic example of the kind of biological analysis that will be expected in a final project: https://www.youtube.com/watch?v=uvyG9yLuNSE. This video tutorial reproduces the analysis of a published neuroscience paper, and while you won't be expected to make new biological discoveries (although that is entirely possible!), you will need to be able to comment and justify every step of analysis that you do, and to discuss and interpret the results of each step (remember: there is no single right answer, just like with the questions in the problem set). This youtube channel, Sanbomics, has many other good video tutorials on analysis:
https://www.youtube.com/@sanbomics.  

There is another possible flavor for the final project: instead of biological analysis, you could attempt to develop a new method or model for a single cell omics task. If you decide to embark down this route, you will need to utilize the scvi-tools framework for developing your project (the developer documentation is here: https://docs.scvi-tools.org/en/stable/developer/index.html). If you're thinking of doing a method development project, we should discuss your ideas.   

Forming a group (applicable for both midterm and final projects)
You can collaborate on your project with anyone you'd like, even if they're not enrolled in the class. You may form groups of 2-4 people for the project, and these people must be listed as authors on your report when you turn the project in, and participate in your presentation. You also need to be sure to acknowledge who you collaborated with (including external collaborators) and describe what each core group member did: just like the author contributions and acknowledgement sections of a paper. It is very important that you understand even if only part of your group is enrolled in the class, you're still responsible for turning in a project meeting the expectations described above. Thus, make sure that your co-authors are motivated to execute the project. 

I have a recommendation when forming a group: try to include people that are strong in the computational aspects, and people that are strong in the biology aspects. This way, you will be able to discuss both computational and biological aspects of the project throughout development, you will learn from each other, and you'll also develop a more interesting project.

Many of the Brazilian students participating in this course have been working with interesting datasets and have strong biological motivations. At the same time, the MBZUAI students come from strong biological backgrounds. 

To help you form groups and find people with complementary skillsets and knowledge, I have started a spreadsheet with everyone attending or auditing this class whose email I have (please correct any information that is wrong in the spreadsheet): 
** Please check piazza for the link to the spreadsheet ** 

(And if you know someone auditing this class who did not get this email, they should fill this form: https://beltrame.mbzuai.ac.ae/auditing)  


Please take some time to fill your project interests in the spreadsheet, so that people know you want to develop a project. For further discussion on project interests, use our Zulip channel: https://scverse.zulipchat.com/#narrow/channel/476882-MBZUAI-Course---Single-Cell-Biology-and-Bioinformatics

This way other students may discover your interests, and you might even find external collaborators ;)
 

### Datasets you can choose

For the projects, you will be free to work with any dataset that includes some kind of data that was generated with single cell omics technologies. This could be single cell RNA sequencing (most common modality), but also spatial transcriptomics, single cell protein sequencing, chromatin accessibility, methylation, or perhaps data from another esoteric single cell assay you find out there. If you don't want to stray into the deep end, I recommend utilizing single cell RNA sequencing data that was generated with 10x Genomics technology, the biggest developer of single cell omics assays. 

There are many public biological data repositories out there, and we will discuss a few of them in class. If you want to keep things simple, I will suggest utilizing data that has been curated by CZI (Chan Zuckerberg Initiative, the largest nonprofit funder of single cell omics research), which you can browse here:
https://cellxgene.cziscience.com/datasets  

You can browse the data online (visualizing embeddings of gene expression) and download the data, which will come in .h5ad format (an h5 format for holding the gene count matrix and associated metadata, described here: https://anndata.readthedocs.io/en/stable/). For reference, a .h5ad file with 10k cells is typically 100-300mb, and with 100k cells anything between 500mb-2GB. This is important because you will often want to load the entire file in memory. If you decide to use your own laptop computer for the project, then by necessity you'll need to work with smaller datasets that fit into memory. 










