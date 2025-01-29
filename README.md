# MLNS-T2SS
Results, Plots, samples, and other supporting files for the paper titled: 

>**Normalizing Flow-Assisted Nested Sampling on Type-II Seesaw Model**
>
>*Rajneil Baruah, Subhadeep Mondal, Sunando Kumar Patra, Satyajit Roy*
>
>[arXiv:2501.16432](https://arxiv.org/abs/2501.16432) [hep-ph]

### Files
The `Plots` directory contains all the plots generated in this analysis.

The `Samples` directory contains all the samples: 
- Final Sample-Object: `nsObjectT2SS.mx`
- Directory Containing all files associated with the Object above: `nsObjectT2SS`
- Final Unweighted Sample with associated likelihood info and `HiggsBounds` info: `17Vec_11Jan_selData.mx`
- sample with 964 points (within 95% CL of all data) to do further analysis: `xsecData23Vec.mx`

The `ML` directory contains all trained networks and associated measurements:
- A learned Distribution object trained on the final unweighted sample: `lrnDist1.mx`
- The Ensemble SNN classifier: `classificationSnnEnsemble_2.wlnet`
- The measurements of the classifier: `classifierMeasures.mx`

### Analysis File

A *Mathematica* notebook is added here: `Data Analysis.nb`

When downloaded along with all other files and folders, this can recreate most of the results in the paper.
