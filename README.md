# RNAseq of Injured Spinal Cord

**Aim:** Screen for differences in differential gene expression following spinal cord injury and transplantation of syngeneic or allogenic mesenchymal stem cells.  

**Study design:** 

* A 75 kdyn SCI was delivered to the spinal cord. MSCs were transplanted 24h post SCI. Mice were sacrificed, spinal cords harvested and RNA isolated at 20 days post SCI.  

* 12 samples (4 study groups, 3 replicates/group).  

**Sequecing:** 

* Illumina HiSeq 2500 High output mode, 2 lanes 2x125bp. 

* Library preparation with Illumina TruSeq strand-specific RNA library prep (poly-A selection). 

**Data analysis:**

* Reads aligned to the reference genome using STAR aligner. 

* limma and edgeR (https://www.bioconductor.org/).

* Implementation in R (v 3.3.2). Key packages: *data.table*, *ggplot2*. 


