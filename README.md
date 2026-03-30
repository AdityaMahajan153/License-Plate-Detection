# 🚗 Automatic Number Plate Recognition (ANPR)

I am working on a project that uses learning and computer vision to recognize vehicle license plates from images. This project uses a model to find the license plate in the image and Google Tesseract to read the characters on the plate.

## 📝 Overview

My system works in two steps to get the best results:

1.  **Localization:** A special model finds the location of the license plate in the image.

2.  **Recognition:** The part of the image with the license plate is processed using **Google Tesseract OCR** to read the characters.

The model is designed to work with English letters and numbers and it works consistently even in different lighting and angles.

## ⚙ Installation & Setup

To get this project working on your computer follow these steps:

1.  **Environment Setup** Create an environment and turn it on:

```bash

python -m venv venv

source venv/bin/activate  # On Windows use: venv\Scripts\activate

```

2.  **Install Dependencies** Install all the libraries using the requirements file:

```bash

pip install -r requirements.txt

```

3.  **Execution Pipeline** Run the Jupyter Notebooks in this order to keep the data workflow going:

1. `Data_Augmentation_and_Pipelining.ipynb.

2. `Number_Plate_Localization.ipynb`

3. `Automatic_Number_Plate_Recognition.ipynb`

## 💡 Project Notes

* **-trained Weights:** I have provided **three sets of -trained model weights** for the Automatic Number Plate Recognition project. You can choose any of these for the localization task in the Automatic Number Plate Recognition project; all have been tested for reliability in the Automatic Number Plate Recognition project.

* **Character Support:** The Automatic Number Plate Recognition project currently only works with **English** letters and numbers.

* **Performance:** The localization model, in the Automatic Number Plate Recognition project works well in most real-world scenarios, which helps the OCR stage in the Automatic Number Plate Recognition project.
