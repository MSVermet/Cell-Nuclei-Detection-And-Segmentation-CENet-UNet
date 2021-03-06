# MSc-Thesis
## Master Information Studies: Data Science track

### Fully-automated nuclei detection and segmentation in medical images using Deep-Learning techniques
*Author: Matty Vermet, University of Amsterdam, submitted in partial fulfillment for the degree of master of science*

Nuclei segmentation plays a crucial role in the analysis of biomedical images. It enables determination of the distribution of certain cell types that are related to diseases such as cancer. Eventhough, it has become a hot topic for research, finding a suitable model that is able to generalize and accurately segment nuclei still remains a difficult problem. In this paper, CE-Net is presented as the model that could potentially be suitable for this problem as it is able to capture high-level information from the features due to pretrained ResNet blocks in the encoder. The model is trained and tested on the PanNuke dataset, which consist of >7000 images from 19 different tissue types. The outcomes on the evaluation metrics of the CE-Net is compared to the medical state-of-the-art model U-Net. The experimental results show that U-Net achieves an average gain over CE-Net of 0.03 on the Jaccard index score and the F1-score, 0.14 on the Cell-Counting Accuracy, and 0.03 on the Panoptic Qualtiy metric. The results also show that U-Net produces more robust predictions and is able to handle a small number of training samples of approximately 250.

<p align="center">
<img src="https://github.com/MSVermet/MSc-Thesis/blob/main/voorkant.jpg" width="400" height="300">


- [Code](https://github.com/MSVermet/MSc-Thesis/tree/main/code) - this folder contains three notebooks with codes: one with U-Net model, CE-Net model, and one where the results of both models are combined

- [Data](https://warwick.ac.uk/fac/cross_fac/tia/data/pannuke) - this is a link to the dataset that is used in this research

- [Thesis](https://github.com/MSVermet/MSc-Thesis/blob/main/MSc_Thesis.pdf) - here you can view the thesis itself

- [Presentation slides](https://github.com/MSVermet/MSc-Thesis/blob/main/Thesis_presentation_slides.pdf) - these are the presentation slides that were presented during the thesis defence
