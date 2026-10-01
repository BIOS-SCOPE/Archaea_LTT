# DADA2 Pipeline used as of MARCH 2026
Read length truncation was dependent of forward and reverse read quality per run. Parameters were left at default settings, using paired end reads. Then samples  with less than 10000 reads were filtered out before calculating the error rate. 

Taxanomic database used here (March 2026) is: Silva v138.2

  ## Note 1
  There is a possibility of the bad resolution of rare Archaea abundance throughout the time series, best to interpret any findings of low abundance groups like MGIV (Hikarachaeia) across seasons carefully using the feature table produced here. My recommendation would be to run forward reads only (Maybe not now that some files were sequenced in reverse) and use the the pool=TRUE parameter.  

  ## Note 2
  Noticed (1 October 2026) that run_751 have swapped primers in the R1 and R2 files, according to the quality plots it seems as if they were run in reverse at the sequencing facility. Will check all the runs.
  
