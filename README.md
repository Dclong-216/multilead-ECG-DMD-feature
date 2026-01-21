# multilead-ECG-DMD-feature-
A MATLAB toolbox for preprocessing multi-lead ECG recordings, generating patient-specific template beats, extracting Dynamic Mode Decomposition (DMD)-based spectral features from 12-lead ECG as an integrated system, constructing longitudinal features across repeated visits.
This repository provides the MATLAB implementation used in our manuscript for multi-lead ECG (12-lead) analysis using Dynamic Mode Decomposition (DMD). The pipeline is designed for offline processing of recorded ECG signals (not real-time streaming) and supports longitudinal modeling for LVH progression prediction based on repeated ECG measurements.
﻿
Key features
﻿
Multi-lead ECG preprocessing: denoising and basic quality control
﻿
Patient-specific template beat generation (DMEANS-based stable beat averaging)
﻿
DMD-based multivariate spectral decomposition treating 12-lead ECG as an integrated system
﻿
Feature extraction: DMD spectral/distribution descriptors (e.g., VLF-related components)
