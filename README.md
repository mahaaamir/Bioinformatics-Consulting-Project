**Client**: <>
  
**Project description as provided by the client:**
We have pool-seq data from pooled individuals in 2 populations and we want to map it to our new genome assembly and pull out markers that exhibit a signature of selection, ie FST outliers. In the past I've used programs like Poppoolation2 but I'm sure there are others. Ideally we could add these markers to a track in our Jbrowser genome site. 

**Overview**:  

Two different populations of a marine species : one from New Jersey and one from California. These populations exhibit slightly different phenotypes with respect to their offspring. (i.e., one makes fewer but bigger babies while the other population makes many but small babies)

25 individuals/ population.
4 libraries of pooled DNA from these 25 individals/ population.
2 replicates for each library. 
Think of it as 4 samples (bay1, bay2, lb1, lb2), 2 runs; so 8 samples in total.

Data: Trimmed, barcode sorted. <everything was run on the same lane> 
 
Goal: Use Wright's F-statistic to identify alleles/sites that differ in frequency due to population substructure. 
