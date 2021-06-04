<h1 align="center">
  <img align="center" src="/misc/img/icon.png"  width="270"></img>
<br>
DocBot
</h1>

# Profile

### Team ID : B21-CAP0362

### Members

* M2082044 - [Nur Imam Masri](https://github.com/nurimammasri)
* M2242154 - [Rafkah Rizqia](https://github.com/rafkahrizqia)
* A0131304 - [Dian Arisma Wicakso](https://github.com/dianarisma86)
* A0141345 - [I Made Ari Widiarsana](https://github.com/widiar)
* C2242155 - [Nurul Uswatun Hasanah](https://github.com/nuruluswatun)

### Roles/personnel

* Project Plan (M2082044 - Nur Imam Masri)
* UI/UX (C2242155 - Nurul Uswatun Hasanah, M2242154 - Rafkah Rizqia)
* Build Machine Learning Model (M2082044 - Nur Imam Masri, M2242154 - Rafkah Rizqia)
* Android Development (A0131304 - Dian Arisma Wicakso, A0141345 - I Made Ari Widiarsana)
* Deployment Application (C2242155 - Nurul Uswatun Hasanah)


[![GitHub stars](https://img.shields.io/github/stars/DocBot-Bangkit-2021/DocBot-MachineLearningModels)](https://github.com/DocBot-Bangkit-2021/DocBot-MachineLearningModels)
[![GitHub forks](https://img.shields.io/github/forks/DocBot-Bangkit-2021/DocBot-MachineLearningModels)](https://github.com/DocBot-Bangkit-2021/DocBot-MachineLearningModels)

# DocBot-ML
This project is our final project for Google Bangkit Academy 2021.

**Android:**
[DocBotApp](https://github.com/DocBot-Bangkit-2021/DocBotApp)

**Cloud:**
[DocBot-Cloud](https://github.com/DocBot-Bangkit-2021/DocBot-Cloud)

**Backgrounder:**

The development of the health sector in Indonesia is still not growing optimally. Public submission of symptoms of disease requires early solutions in dealing with emerging diseases. As well as long-distance service in some areas is still very difficult. The government established an institution, namely Puskesmas, which is a health service facility. Public health problems, especially remote reports, recommendations for early treatment, and appropriate health programs for the community, are still lacking and not yet integrated. The strategy in the form of application development by utilizing deep learning aims to analyze the symptoms of the disease from the community in conducting classification based on disease diagnosis health test data. It is hoped that it can help people who need recommendations for first action against symptoms of disease and related health information, in addition to that expected from the data. which is received can be analyzed by the Puskesmas to design a health program.

**Machine Learning:** 

Building three kinds of models that include [covid detection](https://github.com/DocBot-Bangkit-2021/DocBot-MachineLearningModels/tree/main/Covid-19), [fruit and vegetable nutrition content](https://github.com/DocBot-Bangkit-2021/DocBot-MachineLearningModels/tree/main/FruitsVegetables), and [general disease detection](https://github.com/DocBot-Bangkit-2021/DocBot-MachineLearningModels/tree/main/Disease). Build process using *baseline experiment, early stopping, checkpoint*. Pre-trained model or transfer learning by *resnet152v2, densenet121, inceptionv3, mobilenetv2, vgg19*. The model was saved with *model.tflite* and chosen by the [best model](https://github.com/DocBot-Bangkit-2021/DocBot-MachineLearningModels/tree/main/best%20model) for deployment.

**Case :**

- [x] Covid19 Classification
- [x] Skin and Eye Diseases Classification
- [x] Fruits and Vegetable Classification

**Dataset Link:**

* Covid19 
  * [Early stage symptoms of COVID-19 patient's](https://www.kaggle.com/martuza/early-stage-symptoms-of-covid19-patients)
* Fruits and Vegetables  → Combined Dataset : [FruitsVegetables](https://drive.google.com/file/d/1ruaStccmRUdgpxlI5lD2LDWH9nxoc9VY/view?usp=sharing)
  * Crapping Image on Google Search (Manually)
  * [Fruits-262](https://www.kaggle.com/aelchimminut/fruits262)
  * [Fresh and Stale Images of Fruits and Vegetables](https://www.kaggle.com/raghavrpotdar/fresh-and-stale-images-of-fruits-and-vegetables)
  * [Tomato Cultivars](https://www.kaggle.com/olgabelitskaya/tomato-cultivars)
  * [Kaggle Fruits 360 dataset](https://www.kaggle.com/moltean/fruits)
  * [Fruits & Vegetables](https://www.kaggle.com/jorgebailon/fruits-vegetables)
  * [fruits_vegetables_photos](https://www.kaggle.com/balalexv/fruits-vegetables-photos)

* Disease  → Combined Dataset : [Disease](https://drive.google.com/file/d/1ONPBCD-wRaZp8yY4EplIZImzrm3GYjnC/view?usp=sharing)
  * Crapping Image on Google Search (Manually)
  * [Dermnet](https://www.kaggle.com/shubhamgoel27/dermnet)
  * [Various Skin Diseases Dataset](https://www.kaggle.com/akshitmadan/various-skin-diseases-dataset)

Preview of the image and data used are shown in the picture below.

<img align="center" src="/misc/img/covid.png"></img>

<p align="center">Early stage symptoms of COVID-19 patient's</p>

<img align="center" src="/misc/img/disease.png"></img>

<p align="center">Eye and Skin Disease</p>

<img align="center" src="/misc/img/fruits.png"></img>

<p align="center">Fruits and Vegetables</p>

## Features

- [x] EDA (Exploratory Data Analysis) for Data Tables and Images
- [x] Preprocessing Data and Image
- [x] Image Augmentation
- [x] Callbacks
- [x] EarlyStopping
- [x] ModelCheckpoint
- [x] ResNet152V2
- [x] DenseNet121
- [x] InceptionV3
- [x] MobileNetV2
- [x] VGG19
- [x] TFLite x labels 

## Prerequisites
1. [Jupyter Notebook](https://test-jupyter.readthedocs.io/en/latest/install.html) or [Google Colab](https://colab.research.google.com/)
2. Kaggle API Token → [Generate](https://github.com/Kaggle/kaggle-api#api-credentials)
3. [Python](https://www.python.org/downloads/) version 3.6 or above
4. Latest version of Tensorflow 2.5 (or you can update again by rerunning .ipynb and updating models)

## How to use
1. [Create `kaggle.json` from Kaggle](https://github.com/Kaggle/kaggle-api#api-credentials)
2. Go to your Kaggle profile then download your Kaggle API.
    - My Account  →  Look for API section  →  Create New API Token
3. Open `.ipynb` with Google Colaboratory using `open in colab`
4. "Save a copy in Drive" to run and edit with your account. Click `File` > `Save a copy in Drive` in your Google Colaboratory.
5. Upload your `kaggle.json` if asked to upload it.
6. Will download the dataset on kaggle
7. If using GoogleDrive for the dataset, `GoogleAuth` click on the given link and sign in with your Google Account.
8. Done :)

## References
* [http://bit.ly/papercapstone01](http://bit.ly/papercapstone01)
* [http://bit.ly/papercapstone02](http://bit.ly/papercapstone02) 
* [http://bit.ly/papercapstone03](http://bit.ly/papercapstone03) 
* [http://bit.ly/papercapstone04](http://bit.ly/papercapstone04) 
* [http://bit.ly/papercapstone05](http://bit.ly/papercapstone05) 
* [http://bit.ly/papercapstone06](http://bit.ly/papercapstone06)

## Thank You :)