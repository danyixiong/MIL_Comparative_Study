![QBRC_logo](https://github.com/danyixiong/MIL_Comparative_Study/blob/main/QBRC.jpg)

Researchers searching for more bioinformatics tools please visit Dr. Tao Wang's lab website: https://qbrc.swmed.edu/labs/wanglab/index.php.

# A comparative study of multiple instance learning methods for cancer detection using T-cell receptor sequences
## Description
We review and apply 16 methods to investigate the applicability of multiple instance learning (MIL) to cancer detection using T-cell receptor (TCR) sequences, which hints for a viable approach for large-scale cancer screening, as TCRs can be easily profiled from a subject's peripheral blood. This application is also important as accurate and timely cancer detection is crucial for patients to receive appropriate treatment for best possible prognosis. We consider two feasible data-generating mechanisms, and for the purpose of performance evaluation, we simulate data under each mechanism, where we vary potentially important factors to mimic realistic situations. We also apply the methods to sequencing data for ten cancer types from The Cancer Genome Atlas, as an early proof of concept for distinguishing tumor patients from healthy individuals via TCR sequencing of peripheral blood. We find that given an appropriate MIL method is used, satisfactory performance with Area Under the Receiver Operating Characteristics above 80% can be achieved for five in the ten cancers.

## Implementation
The 16 MIL methods used in our experiments are listed and categorized as below:
| Category  | Method|
| ------------- | ------------- |
| Instance-space (IS) | EMDD,	MI-SVM,	mi-SVM,	SI-SVM,	SI-kNN, MILBoost, mi-Net |
| Bag-space (BS)  | CkNN,	NSK-SVM,	EMD-SVM,	miGraph,	MInD |
| Embedded-space (ES)  | MILES,	BoW,	CCE,	MI-Net |



