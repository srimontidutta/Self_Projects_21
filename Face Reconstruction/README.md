# Face Restoration

Steps to face restoration-

i. Training Data Gathering: Gather pictures of people's faces. 

ii. Training of Recognizer: Feed that face data to the face restorer so that it can learn.

iii. Restoration: Feed new faces of people and see if the trained face restorer model can restore the defective pictures.

## Overview Of This Project

Face Restoration Using Different Architectures:

i. Extra Trees 
ii. K Nearest Neighbors
iii. Linear Regression
iv. Ridge
v. Multi Output 
vi. Gradient Boosting 

Created model takes in the input data of people's faces and shows the results obtained using the above architectures.


## Screenshot Of Output Images
![Face Restoration](https://github.com/srimontidutta/GSSoC21_Projects/raw/main/Face%20Reconstruction/output_imgs.PNG)

## OpenCV Face Recognizers
OpenCV has three built in face recognizers. The names of those face recognizers and their function calls have been given below-

i. EigenFaces Face Recognizer Recognizer - cv2.face.createEigenFaceRecognizer()

ii. FisherFaces Face Recognizer Recognizer - cv2.face.createFisherFaceRecognizer()

iii. Local Binary Patterns Histograms (LBPH) Face Recognizer - cv2.face.createLBPHFaceRecognizer()


## ScreenShots

![Screenshot from 2020-12-11 21-34-18](https://user-images.githubusercontent.com/53366877/110513516-533d4300-812c-11eb-9cde-7566de26682f.png)

![Screenshot from 2020-12-11 17-59-00](https://user-images.githubusercontent.com/53366877/110513613-6ea84e00-812c-11eb-86ec-d3fcecf921be.png)



## Quick Start

- Fork and Clone the repository using-
```
git clone https://github.com/akshitagupta15june/Face-X.git
```
- Create virtual environment-
```
- `python -m venv env`
- `source env/bin/activate` (Linux)
- `env\Scripts\activate` (Windows)
```
- Install dependencies-
```
 pip install -r requirements.txt
```

- Headover to Project Directory- 
```
cd "Recognition using NasNet"
```
- Create dataset using -
```
 python create_dataset.py on respective idle(VS Code, PyCharm, Jupiter Notebook, Colab)
```
Note: Dataset is automatically split into train and val folders.

- Train the model -
```
 python main.py
```
Note: Make sure all dependencies are installed properly.

- Final-output -
```
 python output.py
```