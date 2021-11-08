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

### II part. Quadruplexes

Initially downloaded as two separate BED files, datasets of quadruplexes' (type [Homo Li K](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSM3003539)) were merged into a single file called Quadruplexes_Li_K, which is presented in the data directory.

First part of secondary DNA structure consisted of plotting a corresponding histogram. It illustrated the distribution of intervals among the hg19 genome

![](images/QuadroHomoLiK_histogramZones.png?raw=True)

Further, similar actions were taken to aquire a pie chart of quadruplexeses' arrangement throughout the genome%

![](images/Quadruplexes_LI_K.plotAnnoPie.png?raw=True)

### III part. Intersection 

With a help of bedtools library, a single file was created on the basis of peaks' and quadruplexeses' datasets. Identically to the previous stages, a plot was made as a first step of research:

![](images/histogramIntersection.png?raw=True)

Finally, an independent session was created on the Genome Browser platform. It contains both experiments of histone marks, their merged sequence, selected secondary structure and, finally, the intersection file. While the complex analysis can be taken after visiting the session [itself](https://genome.ucsc.edu/s/young_researcher/hg19_intersection), a particular part of the result is shown below:

![](images/GenomeBrowserSession.png?raw=True)
The captures interval is is chr1:778,593-781,703 3.

The last steps of the study implied two final actions. The former should have been created a new pie chart, showing the distribution of intersection throught DNA zones. At the same time, the latter focused on associating the intersection datasets with the nearest genes.
