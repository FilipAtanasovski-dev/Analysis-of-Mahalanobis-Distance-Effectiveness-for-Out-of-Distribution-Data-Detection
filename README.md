# Mahalanobis Distance for Out-of-Distribution Detection

A deep learning research project investigating **Out-of-Distribution (OOD) detection** using Mahalanobis distance compared with Maximum Softmax Probability (MSP).

The project involved fine-tuning **MobileNetV1/V2** models and analysing their intermediate feature representations across multiple datasets and OOD scenarios, including far-OOD and near-OOD settings.

## What I Worked On

My main contributions focused on:

* Implementing the **Mahalanobis distance OOD scoring pipeline**
* Training and evaluating **MobileNet-based classifiers**
* Implementing and evaluating the **MSP baseline**
* Running experiments across **GTSRB, Tiny-ImageNet and Oxford-IIIT Pet**
* Analysing OOD detection performance across different network layers
* Generating experimental data and visualisations for comparing detection methods
* Analysing the results and contributing to the **Results, Discussion and Introduction** sections of the research paper

## Skills Demonstrated

This project demonstrates my experience with:

* **Python & PyTorch**
* Deep learning and CNN architectures
* **Machine learning experimentation and evaluation**
* Feature-space analysis and statistical methods
* Implementing research papers and ML algorithms
* Working with large image datasets
* Experimental design and quantitative analysis
* Data visualisation and interpretation
* Collaborative research and scientific writing

The project was particularly useful for developing my ability to connect **machine learning models with statistical and mathematical methods**, rather than treating neural networks purely as black-box predictors.
## Contributions

### Filip Atanasovski — 1833103

**Report:** Wrote the Results and Analysis section, substantially revised the Discussion section, and contributed to revisions of the Introduction.

**Code:** Implemented the Mahalanobis Distance scoring function used throughout the experimental pipeline. Trained the GTSRB model and evaluated ImageNet. Implemented and evaluated the MSP baseline across all tested architectures and datasets, including the associated data processing and visualizations.

### Thijmen Schinkelshoek — 1663305

**Report:** Wrote the Background and Related Work, Mahalanobis Distance methodology, and Conclusion sections.

**Code:** Developed much of the project's foundational implementation and structured the code into a reusable experimental pipeline. Improved the training procedure and trained the final GTSRB classifier. Fully implemented the held-out near-OOD experiment and the functionality for multi-layer combination methods.

### Matus Feltovic — 1718657

**Report:** Wrote the Introduction and Discussion sections.

**Code:** Developed the experimental workflow for the MobileNetV1 architecture and trained the corresponding model. Conducted the V1 vs. V2 OOD detection comparison on GTSRB traffic signs, including near-OOD and far-OOD evaluations and the Oxford-as-Is invariant experiments. These experiments showed a narrow performance difference between the two architectures, with V2 performing slightly better.

### Thijmen Adriaansen — 2220822

**Report:** Wrote the Methodology and Experimental Setup sections, assisted with the Results sections, and contributed throughout the report.

**Code:** Improved model accuracy, implemented the far-OOD experiment, and created visualizations of the logistic regression weight distribution.

