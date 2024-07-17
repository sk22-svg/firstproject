# firstproject
Exploring the potential usage of antibody therapies (trastuzumab and bevacizumab) in different cancers using scRNA-seq data on cancer cell lines.

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








