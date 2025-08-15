Retinal Neuropathy & Eye Disease Detection Using AI

Why This Project Matters

Blindness caused by retinal diseases is preventable—if detected early. Unfortunately, millions of people lose their vision due to late diagnosis of conditions like diabetic retinopathy and glaucoma. This project aims to bridge that gap by using Artificial Intelligence to detect retinal neuropathy and related eye diseases from fundus images—fast, accurate, and cost-effective.



What This Project Does

We built an AI-driven solution that:

Analyzes retinal images and classifies disease stages

Uses deep learning for accurate predictions

Provides an easy-to-use web interface for doctors or patients to upload an image and get results instantly

Can be deployed on the cloud for global accessibility



Key Features

✔ Multi-class disease detection (Normal, Mild, Moderate, Severe)
✔ Advanced Transfer Learning models (ResNet50, VGG16) for better accuracy
✔ Data augmentation for robust performance
✔ Real-time prediction via Streamlit web app
✔ Designed for potential deployment on Hugging Face Spaces or AWS



Tech Stack

Language: Python

Deep Learning Framework: TensorFlow, Keras

Image Processing: OpenCV

Deployment: Streamlit

Others: Scikit-learn, Matplotlib, NumPy, Pandas


Project Structure

retinal-neuropathy-detection/
 ├── app/
 │     ├── app.py                
 ├── notebooks/
 │     ├── EDA.ipynb             
 │     ├── Model_Training.ipynb  
 ├── src/
 │     ├── preprocessing.py      
 │     ├── model.py              
 │     ├── predict.py            
 ├── results/                    
 ├── requirements.txt
 ├── README.md
 ├── .gitignore


Dataset:-

The dataset used: APTOS 2019 Blindness Detection

Contains high-resolution retinal fundus images

Labeled across 5 categories: No DR, Mild, Moderate, Severe, Proliferative DR


(Dataset not included in the repository due to size.)


How to Run Locally:-

Step 1: Clone the Repository

git clone https://github.com/your-username/retinal-neuropathy-detection.git
cd retinal-neuropathy-detection

Step 2: Install Dependencies

pip install -r requirements.txt

Step 3: Run the Web App

streamlit run app/app.py


Results (To Be Updated)

Accuracy: Coming soon

Confusion matrix & sample predictions

Real-World Impact:

Imagine a rural clinic with limited access to ophthalmologists—this tool can enable early screening, reduce blindness, and save lives.


License : MIT License

