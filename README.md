Jupyter notebook with the code executing the algorithm for the extraction of traditional measures from 3D models and their classification using Shallow ML (decission trees and linear models), Deep Learning (FCNN), and Tabular Foundation Models (TabPFN v2) discussed in the paper: <br>
Orengo, H.A.; Esmoris, J.; Berganzo-Besga, I.; Lumbreras, F.; Aliende, P.; Wallace, M.; Livarda, A. <br> New computational approaches to morphometrics: combining 3D complex shape representation and machine learning for shape analysis. <br>
Submitted to the Journal of Archaeological Science

Please, use the second version of the code "3DgrainsMLv2_public" (the first version was the submitted initially). The third version incorporates Tabular Foundation Models but it lacks optimistion and GPU integration (can taks multiple hours to excute in Colab). It can be run locally or directly from Google Colab and other environments.

Improvements of the second verision with respect to the orinigal version include:
- Compatibility with Colab and GDrive and other improvements to increase reproducibility
- Higher and more secure parallelisation
- Improvements in the extraction of measures from 3D models
- Improvements in the evaluation and validation of the models

Changes in the third version with respect to the second:
- Incorporates Tabular Foundation Models (TabPFN v2)
- Optimised for GPU use with TabPFN v2
- Improved reproductibility
- More developed documentation

