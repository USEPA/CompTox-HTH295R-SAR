# CompTox-HTH295R-SAR
Contact: paul-friedman.katie@epa.gov

Abstract
Data from a high-throughput human adrenocortical carcinoma assay (HT-H295R) for steroid hormone biosynthesis are available for >2000 chemicals in single concentration and 654 chemicals in multi-concentration (mc). Previously, a metric describing the effect size of a chemical on the biosynthesis of 11 hormones was derived using mc data referred to as the maximum mean Mahalanobis distance (maxmMd). However, mc HT-H295R assay data remain unavailable for many chemicals. This work leverages existing HT-H295R assay data by constructing structure-activity relationships to make predictions for data-poor chemicals, including: (1) identification of individual structural descriptors, known as ToxPrints, associated with increased odds of affecting estrogen or androgen synthesis; (2) a random forest (RF) classifier using physicochemical property descriptors to predict HT-H295R maxmMd binary (positive or negative) outcomes; and, (3) a local approach to predict maxmMd binary outcomes using nearest neighbors (NNs) based on two types of chemical fingerprints (chemotype or Morgan). Individual chemotypes demonstrated high specificity (85-98%) for modulators of estrogen and androgen synthesis but with low sensitivity. The best RF model for maxmMd classification included 13 predicted physicochemical descriptors, yielding a balanced accuracy (BA) of 71% with only modest improvement when hundreds of structural features were added. The best two NN models for binary maxmMd prediction demonstrated BAs of 85 and 81% using chemotype and Morgan fingerprints, respectively. Using an external test set of 6302 chemicals (lacking HT-H295R data), 1241 were identified as putative estrogen and androgen modulators. Combined results across the three classification models (global RF model and two local NN models) predict that 1033 of the 6302 chemicals would be more likely to affect HT-H295R bioactivity. Together, these in silico approaches can efficiently prioritize thousands of untested chemicals for screening to further evaluate their effects on steroid biosynthesis. 

Disclaimer: The United States Environmental Protection Agency (EPA) GitHub project code is provided on an "as is" basis and the user assumes responsibility for its use. EPA has relinquished control of the information and no longer has responsibility to protect the integrity, confidentiality, or availability of the information. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by EPA. The EPA seal and logo shall not be used in any manner to imply endorsement of any commercial product or activity by EPA or the United States Government.

1. What this project does.

This project provides the code associated with the manuscript: Foster et al., "Evaluating structure-based activity in a high-throughput assay for steroid biosynthesis." This code generates all of the analyses and figures found in this manuscript. 

2. Why the project is useful. 

The code included here for Foster et al. enables the following analysis:
•	Structure-activity relationships were constructed with HT-H295R assay data.
•	Chemotypes associated with altered estrogen or androgen synthesis were identified.
•	Random forest modeling used physicochemical descriptors to predict HT-H295R outcomes.
•	Nearest neighbor models used structural similarity to infer HT-H295R outcomes.
•	Together all three approaches inform priority chemicals for screening.

3. How users can get started with the project.

Users can see the code in the .Rmd file and the Supp File 2 has all required inputs. If it is not desired to run the code, the user can refer to the knitted .html file (Supp File 1) that includes all of the outputs of the code.

4. Where users can get help with the project.

Please see Foster et al. "Evaluating structure-based activity in a high-throughput assay for steroid biosynthesis" and for additional questions contact Katie Paul Friedman, paul-friedman.katie@epa.gov.

