<div align="center">
   <h1> (Bachelor Graduation Work)</h1>
   <h3>EfficientNet B0 and B1 built from scratch applied on the Bird multi-class classification</h3>
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

## Architecture (B0 and B1 in sequence)
<img src="images/EfficientNet-B0.png" height="300px">
<img src="images/EfficientNet-B1.png">

## Architecture Blocks (MBConv, SE and Final blocks in sequence)
<div style='vertical-align:middle; display:inline;'>
   <img src="images/MBConv_Block.png">
   <img src="images/Squeeze_and_Execution_Block.png">
   <img src="images/Final_layers.png">
</div>

## Models
- EfficientNet-B0 and B1 models have been built from scratch and applied on the dataset
- Pre-trained B0 and B1 models have been fine-tuned on the dataset
- Results of the fine-tuned models and ones constructed from scratch have been analyzed and compared

## Results
- You can look at "Graduation_Work_Results.xlsx"

## Used methodologies and analysis of results 
- To deeply understand what has been done, you can read the "Bahruz_Huseynov_Graduation_Work.pdf" file
- For the brief information "Project_Brief_Information.pdf" can be read
