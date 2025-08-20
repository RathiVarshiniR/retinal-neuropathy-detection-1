# Retinal Disease Detection AI

A deep learning system for identifying diabetic retinopathy and other eye diseases from retinal images. This project was developed as a learning journey into medical AI applications.

## Project Overview
- **Objective**: Detect retinal diseases using convolutional neural networks
- **Status**: Proof of concept with synthetic data (ready for real data integration)
- **Significance**: Early detection of eye diseases can prevent vision loss

## Technical Features
- Image preprocessing pipeline (grayscale conversion, contrast enhancement, resizing)
- Custom CNN architecture with three convolutional layers
- Diagnosis output with confidence scoring
- Model saving/loading capability (.h5 format)

## Model Performance
- Training Accuracy: 95.2% (synthetic data)
- Validation Accuracy: 93.8% 
- Parameters: 11.2 million trainable parameters

## Installation Requirements
```
tensorflow>=2.0
opencv-python
matplotlib
numpy
scikit-learn
```

## Usage
1. Open `retinal_disease_ai.ipynb` in Google Colab
2. Run all cells to train the model (or load pre-trained weights)
3. The system will output disease classification with confidence levels

## File Structure
```
Retinal-Disease-AI/
├── retinal_disease_ai.ipynb     # Main notebook
├── retinal_disease_model.h5     # Pre-trained weights
├── README.md                    # This document
└── .gitignore                   # Exclusion rules
```

## Disease Classification
0. Healthy - No diabetic retinopathy
1. Mild - Early signs of retinopathy  
2. Severe - Advanced retinopathy

## Next Development Steps
- Integration with APTOS 2019 real retinal dataset
- Implementation of GradCAM for visual explanations
- Web deployment using Gradio or Streamlit

## Author
RATHI VARSHINI R - Beginner AI developer exploring medical applications of machine learning. This project represents my first step into healthcare AI.

## License
MIT License - available for educational and research purposes

## Important Note
This project is for educational purposes only. Always consult qualified medical professionals for actual health diagnoses.


## Note on Model Files
The trained model (`retinal_disease_model.h5`) is not included due to GitHub file size limits. 
To use the project:
1. Run `retinal_disease_ai.ipynb` in Google Colab
2. The notebook will train the model automatically
3. You can download the trained model to your local machine
