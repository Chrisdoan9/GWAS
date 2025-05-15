**Scree plot / elbow plot**: how much information (variance) each principal component (PC) captures from your data.  
Eigenvalue = amount of variation explained by a component

Σ is the covariance matrix:  
	Σ × v = λ × v  
	•	v = eigenvector (PC direction)  
	•	λ = eigenvalue (variance explained by that direction)

plink_results.imiss missingness per **individual** (sample)  
plink_results.lmiss missingness per **locus** (SNP)

FID Family ID  
IID Individual ID

| **F value (roughly)** | **Likely sex genetically**         |
|-----------------------|------------------------------------|
| > 0.8                 | Likely male                        |
| < 0.2                 | Likely female                      |
| 0.2–0.8               | Ambiguous / potential error        |

**inbreeding coefficient** comes from population genetics
