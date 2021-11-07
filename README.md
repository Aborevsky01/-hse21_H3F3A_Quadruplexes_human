# Elective Bioinformatics. Ist research
## Analysis of histone marks and quadruplexes in context of human genome 

### I part. Histone marks

The following picture depicts the distribution of peaks' length among the explored experiments. If speaking about the particuar values, following results can be presented:
1. H3F3A.ENCFF066CSA.hg19.bed contains 376217 peaks (Experiment 1)
2. H3F3A.ENCFF343MZY.hg19.bed contains 314765 peaks (Experiment 2)

![Histogram of peaks' length](images/H3F3A_histogramPeaks.png?raw=True)

Later, the datasets were filtered from the outliers, borders for which had been chosen separately from each other. 

![Histogram of filtered peaks' length](images/H3F3A_peaksFiltered.png?raw=True)

Filtered data allowed to scrutinize the share of histone marks' representation in each type of DNA zones. 

![Pie 1](images/H3F3A.ENCFF066CSA.hg19.filtered.plotAnnoPie.png?raw=True) ![Pie 2](images/H3F3A.ENCFF343MZY.hg19.filtered.plotAnnoPie.png?raw=True)

Finally, two datasets of histone marks were merged into a single one. Its visualization was successfully uploaded to Genome Browser, provement of which can be fould further: [Merged experiments of H3F3A histone mark](https://genome.ucsc.edu/s/young_researcher/hg19_H3F3A)

https://genome.ucsc.edu/s/young_researcher/hg19_intersection
chr1:778,593-781,703 3
