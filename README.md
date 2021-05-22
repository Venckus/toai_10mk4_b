# ToAI_10MK4_B Final Project - Medical visual data segmentation model

<table>
  <tr>
    <td>
      Breast cancer is one of the most common causes of death among women worldwide. Early detection helps in reducing the number of early deaths. The data reviews the medical images of breast cancer using ultrasound scan. Breast Ultrasound Dataset is categorized into three classes: normal, benign, and malignant images. Breast ultrasound images can produce great results in classification, detection, and segmentation of breast cancer when combined with machine learning.  
    </td>
  </tr>
</table>

## Data:
The data collected at baseline include breast ultrasound images among women in ages between 25 and 75 years old. This data was collected in 2018. The number of patients is 600 female patients. The dataset consists of 780 images with an average image size of 500*500 pixels. The images are in PNG format. The ground truth images are presented with original images. The images are categorized into three classes, which are normal, benign, and malignant.
[URL](https://www.kaggle.com/aryashah2k/breast-ultrasound-images-dataset)  

**Citations:**  
_Al-Dhabyani W, Gomaa M, Khaled H, Fahmy A. Dataset of breast ultrasound images. Data in Brief. 2020 Feb;28:104863. DOI: 10.1016/j.dib.2019.104863._
	
	
## Demo:
A working demo can be seen via following URL - https://github.com/Venckus/toai_10mk4_b/blob/main/fastai_v1_unet.ipynb

### Results
The best results accieved using pretrained, imagenet normalized model with Resnet34 architecture. The metrics:
<table>
  <tr>
    <td>Training loss:</td>
    <td>0.174874</td>
  </tr>
  <tr>
    <td>Validation loss:</td>
    <td>0.156018</td>
  </tr>
  <tr>
    <td>Dice:</td>
    <td>0.988534</td>
  </tr>
  <tr>
    <td>Segmentation accuracy:</td>
    <td>0.948120</td>
  </tr>
</table>

## Installation:
Pip:
```
pip install -r requirements.txt
```
Conda:
```
conda install --file requirements.txt
```

## Built with:
- [Python](https://www.python.org) - Python is an interpreted, high-level and general-purpose programming language. Python's design philosophy emphasizes code readability with its notable use of significant whitespace;
- [Jupyter](https://jupyter.org) - Project Jupyter is a nonprofit organization created to "develop open-source software, open-standards, and services for interactive computing across dozens of programming languages". Spun off from IPython in 2014 by Fernando Pérez, Project Jupyter supports execution environments in several dozen languages.
- [Pandas](https://pandas.pydata.org) - In computer programming, pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.
- [Numpy](https://numpy.org/) - NumPy is an open source project aiming to enable numerical computing with Python. 
- [Matplotlib](https://matplotlib.org) - Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+.
- [Fastai](https://github.com/fastai/fastai) - fastai simplifies training fast and accurate neural nets using modern best practices

## Meta:
- Author - Šarūnas Venckus ([email](mailto:), [LinkedIn](https://linkedin.com/in/sarunas-venckus-67831884));
- License - none;
