# corticospinal-pain-signature

This repository contains the code and data accompanying the paper ‘A Corticospinal Signature for Interindividual Pain Sensitivity’. It includes all scripts and resources necessary to reproduce the analyses and results presented in the study.

This repository contains the code accompanying the paper **"A Corticospinal Signature for Interindividual Pain Sensitivity"**. It includes all the Jupyter notebooks used for analyses and figure generation in the study.

---

## Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Notebooks](#notebooks)
  - [CSps_F2.ipynb](#CSps_F2.ipynb)
  - [CSps_F3.ipynb](#CSps_F3.ipynb)
  - [CSps_F4.ipynb](#CSps_F4.ipynb)
  - [CSps_F5.ipynb](#CSps_F5.ipynb)
  - [CSps_F6.ipynb](#CSps_F6.ipynb)

---

## Requirements

- Python 3
- NumPy, SciPy (version 1.13.1), scipy (version 1.11.4), nilearn (version 0.10.3), and scikit-learn (version 1.3.0).

## Notebooks

**CSps_F2.ipynb**

Description: Generates Figure 2 of the paper. This notebook performs model training using Dataset 1 and conducts external validation on Datasets 2 and 3.

Contents:

```
•	Data preprocessing for Dataset 1.
•	Model training and optimization.
•	External validation on Datasets 2 and 3.
•	Visualization of results.
```

**CSps-F3.ipynb**

Description: Conducts confounder analysis and pain specificity analysis using Dataset 4 (task-based fMRI).

Contents:

```
•	Statistical analysis to assess confounders.
•	Pain-specificity analysis in task-based corticospinal fMRI data (Dataset 4).
•	Result interpretation and plotting.
```

**CSps-F4.ipynb**

Description: Performs corticospinal feature importance analysis.

Contents:

```
•	generate Model 1 ~ Model 5
•	Visualization of feature importance.
•	Validation of corticospinal features influencing pain sensitivity.
```

**CSps_F5.ipynb**

Description: Details the CSps (Corticospinal Signature of pain sensitivity) features.

Contents:

```
•	Figures and tables related to CSps features.
```

**CSps_F6.ipynb**

Description: Includes clinical pain prediction and model comparison.

Contents:

```
•	Comparison of different predictive models.
```

---

**License**
-------

This project is licensed under the MIT License.

**Contact**
-------

For questions or further information, please contact:

```
•	Xiaomin Lin
•	Email: linxm@psych.ac.cn
```

Feel free to explore the notebooks and reproduce the analyses. Contributions and feedback are welcome!
