# Mitonuclear Analysis Project
This repository contains data files and scripts to reproduce the analysis for the manuscript currently titled: **"Examination of Mitonuclear Conflict in a Macaque Species Exhibiting Mitonuclear Discordance"**

# Abstract 

Speciation and hybridization are fundamental and intertwined processes in the study of evolution. Hybridization between sufficiently diverged populations can result in genomic conflict within offspring, causing reduced viability and fertility, thus increasing divergence between populations. Conflicts between mitochondrial and nuclear genes are increasingly found to play a role in this process in a variety of systems. We examine the possibility of this conflict in the bear macaque, Macaca arctoides, a primate species exhibiting mitonuclear discordance due to hybridization with two other species groups in its history. Divergence, introgression, and natural selection of mitonuclear genes relative to nuclear control genes were analyzed to determine if there are evolutionary processes involved in resolving the potential conflict caused by mitonuclear discordance. Divergence of mitonuclear genes is increased relative to nuclear genes between M. arctoides and the species of its nuclear ancestry, however there are few signs of differential introgression or selection of mitonuclear genes relative to controls. Although this study detected little evidence of mitonuclear conflict within M. arctoides, the methodology implemented provides a framework that can be used to examine effects of mitonuclear co-introgression and co-evolution in variety of systems.

# Data Analysis

The R scripts used for all statistical analysis and to produce all data figures and model tables are included in the folder ["R-Scripts"](https://github.com/StevisonLab/Mitonuclear-Analysis-Project/tree/master/R-Scripts).

The folder ["Gene-Processing-Scripts"](https://github.com/StevisonLab/Mitonuclear-Analysis-Project/tree/master/Gene-Processing-Scripts)
contains scripts used to convert gene data between different formats and to obtain "matching" data for N-mt and nuclear genes. Dependendencies and authorship of source scripts are stated within scripts.

The folder ["Pop-Gen-Scripts"](https://github.com/StevisonLab/Mitonuclear-Analysis-Project/tree/master/Pop-Gen-Scripts) contains scripts used to run divergence, introgression, and selection analyses on N-mt and nuclear genes. These are all bash scripts designed to loop through programs computing these statistics.