# State of Art Ensembler_architecture For Fire And Smoke Detection
This project implements an ensemble of state-of-the-art deep learning models (DenseNet, ResNet, Xception) to detect forest fires and smoke. The ensemble model, which uses a majority voting scheme, improves detection accuracy over individual models.The ensemble model outperforms individual models in terms of accuracy, precision, recall, and F1 score. The ensemble model achieves an accuracy of 0.99 on the fire dataset and 0.984 on the fire and smoke dataset.

## Introduction
Forest fires pose significant environmental threats, necessitating early and accurate detection systems. This project leverages deep learning techniques to develop a robust forest fire and smoke detection system. The ensemble model achieves high accuracy by combining the strengths of DenseNet, ResNet, and Xception models.

## Tech Stack
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV

## Dataset
The project uses two datasets:
  1) Fire Dataset: Contains images of forest fires.
  2) Fire and Smoke Dataset: Contains images of both forest fires and smoke.

## Installation and Usage
1. Clone the repository:
     git clone https://github.com/SriGopalaKrishnan-R/Advanced-Ensemble-Architecture-For-Accurate-Fire-and-Smoke-Detection/
2. Navigate to the project directory:
     cd code/ 
3. Create a virtual environment and activate it:
     python -m venv venv
     source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
4. Install the required dependencies:
     pip install -r requirements.txt
5. Now use the dataset for training your model and test and then carry out evaluation using performance metrics(Accuracy, Precision, Recall and F1-Score) and performance matrix.
## Contributing
  Contributions are welcome! Please fork the repository and submit a pull request.

## Thank You

