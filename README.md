# Semi-Supervised-Machine-Learning
## Semi Supervised Machine Learning: Multiple Kernal Learning (MKL)- SVM on EEG Data set
### Utilizing MKL-SVM Approach for Semi-Supervised Learning in Schizophrenia Research
**Introduction :** 
The objective of this endeavor is to assess brain connectivity by analyzing electroencephalography (EEG) data collected from both individuals with schizophrenia and healthy counterparts. The research employs the MKL-SVM (Multiple Kernel Learning Support Vector Machine) technique for semi-supervised learning on the provided dataset

**Data and Methodology:**
Incorporating EEG data from 14 individuals with schizophrenia and 14 healthy subjects, the research employs the subsequent approach:

1. Data Preparation: Eliminating artifacts and disturbances from the EEG data.
2. Connectivity Assessment: Quantifying PLV, PLI, and DTF for both initial EEG data and post application of CSD transformation, AVERAGE re-referencing, and REST re-referencing techniques.
3. Graph Theoretical Evaluation: Computing graph theory-derived metrics utilizing adjacency matrices derived from the connectivity measurements

**MKL-SVM Algorithm:**
The MKL-SVM methodology is applied to perform semi-supervised learning on the processed EEG dataset. The procedure comprises the subsequent stages:

1. Feature Extraction: Pertinent attributes, like connectivity metrics or graph-oriented indicators, are derived from the EEG data.
2. Data Labeling: Subsets of the data, such as schizophrenia patients, are labeled, while the remainder remains unlabeled.
3. Kernel Generation: Diverse kernels are formed employing distinct data representations, including PLV, PLI, DTF, or graph-based metrics.
4. Multiple Kernel Learning: The MKL framework is harnessed to discover the optimal kernel amalgamation, capturing discriminative insights from both labeled and unlabeled data.
5. Support Vector Machine: Utilizing the merged kernel matrix, an SVM classifier is trained to categorize unlabeled data and gauge the model's efficacy.

**Findings and Interpretation:** 
The study's outcomes reveal the subsequent observations:

1. In the alpha frequency range, patients with schizophrenia exhibited diminished connectivity strength, reduced clustering coefficient, and shorter characteristic path length in comparison to their healthy counterparts.
2. Within the alpha band, individuals with schizophrenia displayed heightened directional flow originating from the occipital region.
3. Following REST re-referencing, parietal derivations were identified as the sources of alpha activity.
4. Varied connectivity metrics displayed group disparities in fronto-posterior asymmetry, with notable outcomes achieved through CSD transformation, PLV, and DTF. REST re-referencing demonstrated significant variations solely for PLI.
5. REST-derived DTF computations identified inter-hemispheric asymmetry disparities within the groups.

**Conclusion:**
The integration of the MKL-SVM algorithm with diverse connectivity metrics and graph-based indicators yields valuable insights into schizophrenia-related disconnection patterns. The research underscores the significance of encompassing distinct frequency bands and connectivity measures to comprehensively grasp the underlying modifications in brain connectivity associated with psychiatric conditions.

**Future Directions :**
Subsequent endeavors in this domain could encompass:

1. Exploration of supplementary machine learning algorithms and methodologies to enhance classification efficacy.
2. In-depth investigation into the influence of distinct preprocessing procedures and connectivity metrics on outcomes.
3. Broadening the scope of the research to encompass a larger dataset and encompassing a broader array of clinical populations for a comprehensive analysis.


