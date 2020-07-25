---
layout: post
title: Herring larvae RNA QC
subtitle: 
gh-repo: cmurray187/cmurray187.github.io
gh-badge: [star, fork, follow]
tags: [research, Pacific herring, RNA]
comments: true
---

I sent 16 larvae (one per replicare tank) to UW's Functional Genomics Core for a pilot RNA extraction and QC. The extraction was completed by Dr. Sengkeo Srinouanprachanh on 7/2/2020.

RNA extracted using Zymo RNA Mini Kit. QC done using Eukaryote Total RNA Pico in Agilent 2100 bioanalyzer. 

RNA quality varied between samples. See the electropherograms below:


**Replicates 1-8**

<img src="https://raw.githubusercontent.com/cmurray187/cmurray187.github.io/master/notebookimages/July%2017%20Herring%20RNA%20QC/RIN_tanks1-8.PNG" width="400" height="400">

**Replicates 9-16**

<img src="https://raw.githubusercontent.com/cmurray187/cmurray187.github.io/master/notebookimages/July%2017%20Herring%20RNA%20QC/RIN_tanks9-16.PNG" width="400" height="400">

A conservative cutoff for RIN is ~7, although samples with slightly lowers RINs could be accounted for during analysis. We that that 10/16 samples had RIN > 7, 3 samples > 6, and 3 samples < 6. 

## Next  Steps
I have ~15 more samples per replicate tank preserved in RNAlater. Based on the images I took of the original larvae used for this pilot, evidence for visual degradation is a reltively good marker for RNA quality. I'm optomistic that there are a few winners from each replicate vial for a high quality analysis. 


## A note on RIN values
RIN is an algorithm based on a selection of features (Schroeder et al., 2006)[https://bmcmolbiol.biomedcentral.com/articles/10.1186/1471-2199-7-3]. Important qualities include (from Schroeder et al.) 
1.	The total RNA ratio measures the fraction of the area in the region of 18S and 28S compared to the total area under the curve and reflects the proportion of large molecules compared to smaller ones. It has large values for categories 6 to 10.
2.	The height of the 28S peak contributes additional information about the state of the degradation process, i.e. during degradation, the 28S band disappears faster than the 18S band. Therefore, it allows detection of a beginning degradation. It has largest values for categories 9 and 10, and zero values for categories 1 to 3.
3.	The fast area ratio reflects how far the degradation proceeded and has typically larger values for the categories 3 to 6.
4.	The marker height has large values for categories 1 and 2 and small values for all other categories since short degradation products will overlap with the lower marker.
 
**Segments of an electropherogram**
<img src="https://raw.githubusercontent.com/cmurray187/cmurray187.github.io/master/notebookimages/July%2017%20Herring%20RNA%20QC/Segments%20of%20an%20electropherogram.png" width="400" height="400">


