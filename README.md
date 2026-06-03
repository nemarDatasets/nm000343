[![DOI](https://img.shields.io/badge/DOI-10.82901%2Fnemar.nm000343-blue)](https://doi.org/10.82901/nemar.nm000343)

Hinss2021
=========

Neuroergonomic 2021 dataset.

Dataset Overview
----------------
  Code: Hinss2021
  Paradigm: rstate
  DOI: 10.1038/s41597-022-01898-y
  Subjects: 15
  Sessions per subject: 2
  Events: rs=1, easy=2, medium=3, diff=4
  Trial interval: [0, 2] s
  File format: set

Acquisition
-----------
  Sampling rate: 500.0 Hz
  Number of channels: 62
  Channel types: eeg=62
  Channel names: AF3, AF4, AF7, AF8, AFz, C1, C2, C3, C4, C5, C6, CP1, CP2, CP3, CP4, CP5, CP6, CPz, F1, F2, F3, F4, F5, F6, F7, F8, FC1, FC2, FC3, FC4, FC5, FC6, FCz, FT10, FT7, FT8, FT9, Fp1, Fp2, Fz, O1, O2, Oz, P1, P2, P3, P4, P5, P6, P7, P8, PO3, PO4, PO7, PO8, POz, Pz, T7, T8, TP7, TP8
  Montage: standard_1020
  Hardware: ActiCHamp (Brain Products Gmbh)
  Reference: Fpz
  Sensor type: active Ag/AgCl
  Line frequency: 50.0 Hz
  Impedance threshold: 25 kOhm
  Auxiliary channels: ecg

Participants
------------
  Number of subjects: 15
  Health status: healthy
  Age: mean=23.9
  Gender distribution: female=11, male=18

Experimental Protocol
---------------------
  Paradigm: rstate
  Number of classes: 4
  Class labels: rs, easy, medium, diff
  Study design: Passive BCI neuroergonomics dataset with resting state and 3 difficulty levels of MATB-II task (easy, medium, difficult). The MOABB loader provides resting state and MATB conditions only.
  Feedback type: none
  Stimulus type: visual display
  Training/test split: False

HED Event Annotations
---------------------
  Schema: HED 8.4.0 | Browse: https://www.hedtags.org/hed-schema-browser

  rs
    ├─ Experiment-structure
    └─ Rest

  easy
    ├─ Experiment-structure
    └─ Label/easy

  medium
    ├─ Experiment-structure
    └─ Label/medium

  diff
    ├─ Experiment-structure
    └─ Label/difficult

Paradigm-Specific Parameters
----------------------------
  Detected paradigm: resting_state

Data Structure
--------------
  Trials: 90
  Trials context: total

Preprocessing
-------------
  Data state: raw
  Preprocessing applied: False

Signal Processing
-----------------
  Classifiers: MDM, Riemannian
  Feature extraction: Bandpower, Covariance/Riemannian, ICA
  Frequency bands: alpha=[8.0, 13.0] Hz; theta=[4.0, 8.0] Hz

Cross-Validation
----------------
  Method: 5-fold
  Folds: 5
  Evaluation type: cross_subject, cross_session, transfer_learning

Performance (Original Study)
----------------------------
  Accuracy: 70.67%

BCI Application
---------------
  Applications: neuroergonomics, mental_workload_estimation
  Environment: laboratory

Tags
----
  Pathology: Healthy
  Modality: Cognitive
  Type: Research

Documentation
-------------
  DOI: 10.1038/s41597-022-01898-y
  License: CC-BY-SA-4.0
  Investigators: Marcel F. Hinss, Emilie S. Jahanpour, Bertille Somon, Lou Pluchon, Frédéric Dehais, Raphaëlle N. Roy
  Senior author: Raphaëlle N. Roy
  Contact: marcel.hinss@isae-supaero.fr
  Institution: ISAE-SUPAERO, Université de Toulouse
  Department: Department of Information Processing and Systems
  Address: Toulouse, France
  Country: FR
  Repository: Zenodo
  Data URL: https://doi.org/10.5281/zenodo.6874128
  Publication year: 2023
  Funding: ERASMUS program; ANITI (Artificial and Natural Intelligence Toulouse Institute)
  Ethics approval: Comité d'Éthique de la Recherche (CER), Université de Toulouse (CER number 2021-342)
  Acknowledgements: This research was supported in part by the ERASMUS program (which funded Mr Hinss' internship), and by ANITI (Artificial and Natural Intelligence Toulouse Institute), Toulouse, France.
  How to acknowledge: Please cite: Hinss et al. (2023). Open multi-session and multi-task EEG cognitive dataset for passive brain-computer interface applications. Scientific Data, 10, 85. https://doi.org/10.1038/s41597-022-01898-y

References
----------
.. [Hinss2021] M. Hinss, B. Somon, F. Dehais & R. N. Roy (2021) Open EEG Datasets for Passive Brain-Computer Interface Applications: Lacks and Perspectives. IEEE Neural Engineering Conference.

.. [Hinss2023] M. F. Hinss, et al. (2023) An EEG dataset for cross-session mental workload estimation: Passive BCI competition of the Neuroergonomics Conference 2021. Scientific Data, 10, 85. https://doi.org/10.1038/s41597-022-01898-y
Appelhoff, S., Sanderson, M., Brooks, T., Vliet, M., Quentin, R., Holdgraf, C., Chaumon, M., Mikulan, E., Tavabi, K., Hochenberger, R., Welke, D., Brunner, C., Rockhill, A., Larson, E., Gramfort, A. and Jas, M. (2019). MNE-BIDS: Organizing electrophysiological data into the BIDS format and facilitating their analysis. Journal of Open Source Software 4: (1896). https://doi.org/10.21105/joss.01896

Pernet, C. R., Appelhoff, S., Gorgolewski, K. J., Flandin, G., Phillips, C., Delorme, A., Oostenveld, R. (2019). EEG-BIDS, an extension to the brain imaging data structure for electroencephalography. Scientific Data, 6, 103. https://doi.org/10.1038/s41597-019-0104-8

---
Generated by MOABB 1.5.0 (Mother of All BCI Benchmarks)
https://github.com/NeuroTechX/moabb
