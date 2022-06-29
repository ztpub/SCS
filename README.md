# SCS: Single-sample controller strategy

This is a backup repository of matlab package for single-sample controller strategy (SCS).

Motivation: It is a challenging task to discover personalized driver genes that provide crucial information on disease risk and drug sensitivity for individual patients. However, few methods have been proposed to identify the personalized-sample driver genes from the cancer omics data due to the lack of samples for each individual. To circumvent this problem, here we present a novel single-sample controller strategy (SCS) to identify personalized driver mutation profiles from network controllability perspective.

Results: SCS integrates mutation data and expression data into a reference molecular network for each patient to obtain the driver mutation profiles in a personalized-sample manner. This is the first such a computational framework, to bridge the personalized driver mutation discovery problem and the structural network controllability problem. The key idea of SCS is to detect those mutated genes which can achieve the transition from the normal state to the disease state based on each individual omics data from network controllability perspective. We widely validate the driver mutation profiles of our SCS from three aspects: (i) the improved precision for the predicted driver genes in the population compared with other driver-focus methods; (ii) the effectiveness for discovering the personalized driver genes and (iii) the application to the risk assessment through the integration of the driver mutation signature and expression data, respectively, across the five distinct benchmarks from The Cancer Genome Atlas. In conclusion, our SCS makes efficient and robust personalized driver mutation profiles predictions, opening new avenues in personalized medicine and targeted cancer therapy.

# Reference:
Guo WF, Zhang SW, Liu LL, Liu F, Shi QQ, Zhang L, Tang Y, Zeng T, Chen L. Discovering personalized driver mutation profiles of single samples in cancer by network control strategy. Bioinformatics. 2018 Jun 1;34(11):1893-1903. doi: 10.1093/bioinformatics/bty006. PMID: 29329368.

Code issues can contact: Weifeng Guo (guowf@zzu.edu.cn); or Tao Zeng (zengtao@sibs.ac.cn, zeng_tao@gzlab.ac.cn)
