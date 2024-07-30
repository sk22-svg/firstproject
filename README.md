# firstproject
Exploring the potential usage of antibody therapies (trastuzumab and bevacizumab) in different cancers using scRNA-seq data on cancer cell lines.
# https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8135089/

The key scientific question (KSQ) -  Using available scRNA-seq data from cancer cell lines, how would you explore the use of the following FDA-approved antibody therapies in additional cancers?

Trastuzumab: Targets HER2 and is used in the treatment of HER2-positive breast and gastric cancers.

Bevacizumab: Targets VEGF and is used for a variety of cancers, including colorectal, lung, glioblastoma, breast, liver, and kidney cancer.

First, what is scRNA-seq data? – Single cell RNA seq (scRNA-seq) data is the mRNA (or “transcriptome”) sequence present in an individual cell of a specific tissue. Since cells in a particular tissue are not homogenous with respect to the genes they express and the quantity of proteins present, it is important to profile individual cells respectively for a protein’s level and not consider all the cells as  one unit. Benefit of doing this is that the protein levels in every cell are ascertained and can be compared with each other to determine whether a protein is deregulated in some cells and upregulated in others. 

A good introduction of single cell RNA sequencing is here:
https://youtu.be/uFrrKHB9weY?si=LIvKhg6q54ciiKp1

What are cancer cell lines ? Why are we using them for modeling cancer?
Since researchers cannot use humans to test the drugs developed against cancer, we use cell lines (a bunch of cells from a tissue grown in a lab). Cancer cell lines are distinct from normal cell lines in that they grow indefinitely and abnormally compared to normal cells.  This trait makes the cancer cell lines “model organisms” for testing the efficacies of different cancer therapies. 

 What is the question asking to do ? – 
Genes which are responsible for different cancers → seeing their expression changes in trastuzumab given patients → seeing whether those  genes are getting upregulated or downregulated in trastuzumab given patients → can comment on whether trastuzumab should be given for other cancers also or not. 

Same is for bevacizumab :
Genes which are responsible for different cancers → seeing their expression changes in bevacizumab given patients → seeing whether those  genes are getting upregulated or downregulated in bevacizumab given patients → can comment on whether bevacizumab should be given for other cancers also or not. 

Not understood – how will this monoclonal antibody help in different cancers, if it is monoclonal?

Test your knowledge about the paper ! # https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8135089/

1) How did the authors handle the potential caveat of co-culturing cell lines before profiling by scRNA-seq? Why do you think that caveat was or was not adequately addressed?
   --> The authors managed to overcome the caveat well by ensuring that the patterns of heterogeneity were as similar between cell lines from the same pool as between cell lines of different pools and they performed a control experiment in which six cell lines were profiled with and without co-culturing for 3 days. Co-culturing had a small effect on average gene expression in each cell line, while patterns of heterogeneity were highly consistent between the two conditions which were the focus of this study.

   2) The authors identified discrete subpopulations of cells within a subset of individual cell lines (Fig. 2A-B). What might be the reason why some cell lines have these discrete subpopulations while others do not?
   --> Discrete clusters of cells within a cell line were found only for a minority (11%) of the cell lines:  For each such cluster, the authors identified the top 50 upregulated genes compared to all other cells from the same cell line. These expression programs showed limited similarities to one another, both within cell lines of the same cancer type and across different cancer types, indicating that discrete subpopulations are typically unique and cell line-specific.

   3) What are Recurrent Heterogeneous Programs (RHPs) and how were they defined?
   --> Recurrent Heterogenous Programs (RHPs) were features of the cell lines for which they were heterogenous in their genetic expression between multiple cell lines and between multiple human tumors.

  4) How do the identified RHPs relate to in vivo programs of heterogeneity in tumors, and what evidence supports this relationship?
     --> The identified RHPs were related to in vivo programs of heterogeneity in tumors by comparing the functional annotation of "signature genes" in cell lines and in vivo tumors.
     The in vivo relevance of cell line RHPs was showed by a combined analysis of cells from cell lines and tumors, demonstrating their common patterns of variation.






