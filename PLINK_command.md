Some gcta version installed but didn't work, try other version. Most update version may not work.  
Simulated phenotypes data using GCTA with the 1KG EAS dataset.
```
gcta  \
  --bfile 1KG.EAS.auto.snp.norm.nodup.split.rare002.common015.missing \
  --simu-cc 250 254  \
  --simu-causal-loci causal.snplist  \
  --simu-hsq 0.8  \
  --simu-k 0.5  \
  --simu-rep 1  \
  --out 1kgeas_binary
```
