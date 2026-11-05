# EarSense: Development of a Reduced-Channel Wearable Ear-Based EEG System for P300 Detection

**Minor and Major Project | Biomedical Engineering | SRM Institute of Science and Technology**

## 1. Project Overview

EarSense is a biomedical engineering research and development project focused on developing a compact, wearable, ear-based Electroencephalography (EEG) system for detecting and classifying P300 Event-Related Potentials (ERPs).

Conventional EEG systems typically require multiple scalp electrodes and dedicated acquisition setups. EarSense investigates whether meaningful P300-related information can be captured using a reduced number of electrodes positioned around the ear, offering a potential pathway towards more compact and wearable EEG acquisition.

The project integrates biological EEG validation, electrode and hardware design, signal processing, feature selection, and machine-learning-based classification.

The central objective is to determine the minimum effective electrode configuration and signal-processing pipeline required for reliable P300 detection, and subsequently translate these experimentally validated requirements into a wearable hardware system.

## 2. Research Objectives

- Investigate the biological feasibility of detecting P300 responses using ear-based EEG.
- Optimise electrode configurations to identify the minimum effective number of channels.
- Evaluate electrode impedance, signal quality, contact stability, and signal-to-noise characteristics.
- Develop an independent EEG preprocessing and artifact-handling pipeline.
- Extract and select informative P300-related signal features.
- Compare machine-learning models for target and non-target classification.
- Translate validated biological and algorithmic requirements into a compact EEG acquisition circuit and wearable PCB design.
- Develop and evaluate an integrated ear-mounted EEG prototype.

## 3. Proposed Methodology

The project follows a sequential research and engineering workflow:

### A. Biological Validation and P300 Detection

- Establish a controlled P300 experimental paradigm.
- Analyse target and non-target EEG responses.
- Evaluate P300 amplitude, latency, waveform differences, signal quality, and signal-to-noise characteristics.
- Establish the biological feasibility of P300 detection.

### B. Electrode Configuration and Channel Optimisation

- Investigate progressively reduced electrode configurations.
- Evaluate individual channel contributions.
- Compare configurations based on P300 detectability, signal quality, and classification performance.
- Identify the minimum effective electrode configuration.

### C. Signal Processing and Artifact Handling

Develop an independent EEG processing pipeline:

**Raw EEG → Signal Quality Assessment → Filtering → Artifact Handling → Epoch Segmentation → Baseline Correction → Feature Extraction → Feature Selection → Classification**

The pipeline addresses baseline drift, power-line interference, high-frequency noise, signal instability, and motion-related artifacts.

Potential artifacts include eye blinks, facial muscle activity, jaw movement, head movement, and electrode displacement.

### D. Feature Extraction and Selection

Investigate relevant signal characteristics, including:

- P300 peak amplitude and latency.
- Mean amplitude within selected time windows.
- Signal slope and waveform area.
- Statistical features such as mean, variance, standard deviation, skewness, and kurtosis.
- Relevant frequency-domain and signal-power characteristics.

Feature-selection approaches may include Mutual Information, Recursive Feature Elimination, Random Forest feature importance, and dimensionality-reduction methods.

### E. Machine Learning and Classification

Evaluate computationally efficient classification algorithms for distinguishing target and non-target P300 responses:

- Linear Discriminant Analysis (LDA)
- Support Vector Machine (SVM)
- Random Forest

Model performance will be assessed using accuracy, precision, recall, F1-score, and confusion matrices.

### F. Hardware Design and PCB Development

Translate the experimentally validated channel and processing requirements into the hardware architecture.

The hardware development phase involves:

- EEG acquisition circuit design.
- Signal conditioning and amplification.
- Analog filtering.
- Analog-to-Digital Conversion (ADC) integration.
- Microcontroller-based processing.
- Communication and power-management considerations.
- Circuit simulation and verification.
- PCB layout design and component integration.

The hardware architecture will be guided by the validated electrode configuration and system requirements rather than an arbitrary predetermined channel count.

### G. Wearable Prototype Development and Evaluation

The final system will integrate the electrode arrangement, acquisition electronics, and wearable mechanical design.

Evaluation will consider biological performance, signal quality, classification performance, hardware stability, communication, power requirements, and wearability.

## 4. Development Structure

### Minor Project – Research and System Requirement Validation

Focuses on establishing the biological and algorithmic requirements of EarSense.

Key activities:
- Literature review and experimental design.
- P300 EEG acquisition and biological validation.
- Electrode and channel optimisation.
- Signal preprocessing and artifact analysis.
- Feature extraction and selection.
- Machine-learning classification.
- Model validation and identification of the minimum effective system.

**Expected outcome:** A validated set of requirements defining the electrode configuration, channel count, signal-processing stages, relevant features, and suitable classification approach.

### Major Project – Hardware Development and System Integration

Focuses on translating the validated requirements into a functional wearable EEG system.

Key activities:
- Electrode integration and mechanical design.
- EEG acquisition circuitry.
- Circuit simulation and PCB development.
- Signal conditioning, amplification, and filtering.
- ADC and microcontroller integration.
- Communication and power management.
- Prototype development and integrated system testing.

**Expected outcome:** A functional wearable EarSense prototype based on experimentally validated biological and algorithmic requirements.

## 5. Current Development Status

The project is progressing across computational analysis and hardware development.

- P300 EEG analysis and signal-processing workflow.
- Investigation of reduced-channel ear-based EEG.
- Exploration of P300 classification approaches.
- Electronic circuit design and simulation.
- PCB design and hardware architecture development.

Further development will focus on completing the hardware design, prototype fabrication, integration, and experimental evaluation.

## 6. Expected Research Contribution

EarSense proposes an integrated approach to wearable EEG development by connecting biological validation, channel optimisation, signal processing, feature selection, machine-learning classification, and hardware engineering.

Rather than treating these as independent components, the project follows a sequential design approach:

1. Biological analysis determines what signal information is available.
2. Channel optimisation determines where and with how many electrodes it can be captured.
3. Feature selection identifies the information necessary for classification.
4. Machine-learning evaluation determines how efficiently the information can be interpreted.
5. Hardware development translates the validated requirements into a wearable system.

The broader aim is to investigate a practical, reduced-channel approach to P300 detection through ear-based EEG acquisition.

## 7. Project Information

| Category | Details |
|---|---|
| Project | EarSense |
| Project Type | Minor and Major
