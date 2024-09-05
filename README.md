# Classification-of-Lung-Respiratory-Sounds
This repository presents a study on applying machine learning to lung auscultation for enhanced diagnostic accuracy. Utilizing a Kaggle dataset, CNNs, ANNs, SVMs, and RFs were implemented and compared for classifying pulmonary disorders, demonstrating ML's potential in advancing precision medicine.

## Introduction
- This repository provides Python and R scripts designed for the classification of lung sounds using various machine learning algorithms.
- The project uses a comprehensive dataset of lung auscultation sounds, analyzing them to detect patterns associated with different respiratory conditions.
- **Important:** Please follow the provided instructions carefully to ensure proper execution of the scripts, particularly the handling of audio files and model training phases.

## Demo Video

[![Watch the video](githubAssets/demo_thumbnail.png)](https://drive.google.com/file/d/150W0rOrV0d4w68vspjjVJ3Ylge9kvH74/view?usp=drive_link)

## Motivation
Lung auscultation remains a critical diagnostic tool in healthcare, yet the interpretation of lung sounds is prone to variability between clinicians. This project aims to mitigate this issue by leveraging machine learning to enhance diagnostic precision, ensuring consistent and reliable assessments.

## Features
- **Deep Learning (DL) Algorithms:** Implementations of Convolutional Neural Networks (CNNs) and Artificial Neural Networks (ANNs) for lung sound classification.
- **Traditional ML Algorithms:** Support Vector Machines (SVMs) and Random Forests (RFs) are used for comparison.
- **Data Preprocessing:** Audio preprocessing techniques including noise reduction, normalization, and feature extraction using Mel-frequency cepstral coefficients (MFCCs).
- **Visualization Tools:** ROC curves, confusion matrices, and precision-recall curves to evaluate model performance.

## Usage

### Running the Python Scripts (CNN & ANN)
  - Ensure Python 3.x is installed.
  - To classify lung sounds using CNN or ANN, execute:
    ```bash
      python CNN & ANN.ipynb
    ```
  - View the output results and confusion matrices for accuracy and performance analysis.

### Running the R Scripts (SVM & RF)
  - Load the dataset and execute:
    ```bash
      Rscript SVM and RF.Rmd
    ```

## Getting Started

### Prerequisites
  - Python 3.x for deep learning models
  - R 4.4.0 for SVM and Random Forest models
  - Libraries: `TensorFlow`, `Keras`, `scikit-learn`, `pandas`, `librosa` (for Python) and `tidyverse`, `randomForest`, `e1071` (for R).

### Installation
Clone the repository:
  ```bash
    git clone https://github.com/AFLucas-UOM/Classification-of-Lung-Respiratory-Sounds.git
  ```

## Resources

- [Project Report (PDF)](https://github.com/AFLucas-UOM/Classification-of-Lung-Respiratory-Sounds/blob/main/0.%20Plagiarism%20Form%2C%20Documentation%2C%20Presentation%20%26%20Video/1.%20Classification%20of%20Lung%20Respiratory%20Sounds%20-%20iAPT.pdf) 
- [Kaggle Dataset](https://www.kaggle.com/datasets/vbookshelf/respiratory-sound-database) for respiratory sound classification.

## Results

- **CNN**: Achieved a classification accuracy of 90% after training for 74 epochs.
- **ANN**: Demonstrated the highest accuracy of 92% with a batch size of 5.
- **SVM**: Performed moderately, with an accuracy of 70%.
- **RF**: Outperformed SVM, achieving a classification accuracy of 74%.

### Model Performance Summary:

- **CNN**: 90% accuracy
- **ANN**: 92% accuracy
- **SVM**: 70% accuracy
- **RF**: 74% accuracy

## Contribution

Contributions to improve the code, add new features, or optimize model performance are welcome! Fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was developed as part of the `ARI2201` course at the `University of Malta`, under the supervision of `Dr. Kristian Guillaumier`.

## Contact

For inquiries or feedback, please contact [Andrea Filiberto Lucas](mailto:andrealucasmalta@gmail.com).
