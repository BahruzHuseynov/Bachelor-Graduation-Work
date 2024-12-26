<div align="center">
   <h2>EfficientNet B0 and B1 built from scratch applied on the Bird Multi-class classification</h2>
   <h1> (Bachelor Graduation Work)</h1>
   <img src = "images/BHOS_logo.png" alt="BHOS Logo">
</div>

It is a research based project in which the main purpose was to apply EfficientNet from scratch with varying hyperparameters and compare the results with the pre-trained and fine-tuned models.

## Technology
- **Python**: Main programming language. <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt = "Python" height="30" >
- **PyTorch**: Machine Learning framework. <img src="https://github.com/tandpfun/skill-icons/blob/main/icons/PyTorch-Dark.svg" alt="PyTorch" height="30" />
- **Scikit-learn**: An open-source library in Python that helps us implement machine learning models. <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/2560px-Scikit_learn_logo_small.svg.png" alt="Scikit-learn"  height="30" />

## Main Dataset: <a href="https://paperswithcode.com/dataset/cub-200-2011"> CUB-200-2011 (Caltech-UCSD Birds-200-2011) </a> 
- 11 788 bird images
- 200 labels
- Each consists of 50-60 images
- Bird images with different shapes (500x500, 200x200), positions (flying, swimming) and quality

## The second dataset:
- 3324 bird images
- 20 labels
- All images have the static shape of 224x224
- Regular quality

## Pipeline
<div align="center">
   <img src="images/Pipeline_Main.png" alt="Pipeline" width="700">
</div>

## Pre-trained parameters
- The folder contains .pt files of YOLOv8 and RT-DETR detection models which are the saved parameters of best YOLOv8 and best RT-DETR models represented in Lego_Results.xlsx (located under Results folder)

## Models
- Jupyter Notebook named "Fine-Tuning Detection Models" is used to fine-tune the YOLOv8 and RT-DETR and save the parameters
- data.yaml file is used in the training procedure of the detection models, which contains data path, augmentation types and other needy information
- Jupyter Notebook named "Fine-Tuned RTDETR + DeepSORT" is a combination of the Detection-Tracking pipeline. YOLOv8 can also be used instead of RT-DETR with some minor changes.

## Results
- The folder contains Lego_Results.xlsx which has all saved values during the execution of the codes
- There are also some figures underlining important points obtained from the experiments

