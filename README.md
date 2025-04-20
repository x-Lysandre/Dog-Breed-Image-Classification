# Dog-Breed-Image-Classification
## 🐶 Dog Breed Image Classification  
A deep learning project that classifies over 100 dog breeds from images using Convolutional Neural Networks (CNNs), powered by TensorFlow and Keras. Built on top of the Stanford Dogs Dataset (via Kaggle), this project aims to accurately identify dog breeds with high accuracy using transfer learning and image augmentation techniques.  


## 🚀 Features
Classifies 120+ dog breeds from images

Utilizes TensorFlow/Keras and pre-trained CNN models

Implements image augmentation to improve generalization

Fine-tuned using Transfer Learning (e.g., MobileNet, ResNet)

Achieved ~89% validation accuracy

Interactive exploration through Jupyter Notebook  

## 🧠 Model Architecture  
### Preprocessing:

Image resizing, normalization, and augmentation (rotation, flipping, zoom)  
![image](https://github.com/user-attachments/assets/9daa7cdf-ce3b-47a3-940c-8a7e42ca085c)


### Model:

Transfer Learning using a pre-trained CNN (e.g., MobileNetV2)

Custom dense layers for classification  

### Training:

Categorical cross-entropy loss

Adam optimizer

Early stopping and learning rate scheduler for optimization  




### 📁 Project Structure
mathematica
Copy
Edit
📦 Dog-Breed-Image-Classification  
 ┣ 📜 dog_breed_identification.ipynb   ← Main notebook     
 ┗ 📜 README.md                        ← You're here     
  
### 📊 Results
Accuracy: ~89% on validation data

Loss Curves & Confusion Matrix included in the notebook

Shows strong generalization on unseen images 
![image](https://github.com/user-attachments/assets/ca561dd0-9f4c-49e6-8e2a-fbabaa33c130)



## 🛠️ Tools & Libraries Used
Python

TensorFlow / Keras

OpenCV

NumPy / Pandas

Matplotlib / Seaborn

Jupyter Notebook

## 🧪 How to Run
Clone this repo:

bash
Copy
Edit
git clone https://github.com/x-Lysandre/Dog-Breed-Image-Classification.git
cd Dog-Breed-Image-Classification
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Open dog_breed_identification.ipynb and run all cells.  

## 📦 Dataset
The dataset is available on Kaggle - Dog Breed Identification. You’ll need to download it manually and place it in the input/ folder.  

## 📸 Sample Output
The model correctly predicts breeds like Labrador, German Shepherd, Pug, etc., from raw image input.  
![image](https://github.com/user-attachments/assets/4409418d-bdc5-43e0-8b30-672a01b95d4a)



## 🙌 Acknowledgments
Kaggle Dog Breed Identification Challenge  

Stanford Dogs Dataset

TensorFlow/Keras documentation  

## 📬 Contact
For any queries or collaborations, feel free to reach out:
📧 negivj3000@gmail.com

