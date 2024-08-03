# Brain Tumor Detection with FastAPI
## Overview
This repository contains a FastAPI-based web application designed for brain tumor detection using machine learning models. The project integrates three distinct models to analyze MRI scans and provide comprehensive insights:

1. Detection of Tumor Presence
2. Tumor Localization
3. Tumor Type Classification

## Features
- **MRI Scan Analysis:** Upload and analyze MRI scans for various aspects of brain tumor detection.
- **Real-time Predictions:** Immediate results with a user-friendly web interface.
- **Model Integration:** Utilizes three specialized models for detailed analysis.
## Models
1. **First Model: Tumor Presence Detection**

   - **Description:** This model determines whether an MRI scan indicates the presence of a tumor.
   - **Link**: [First Model](https://www.kaggle.com/code/abdelrahmankamel/bt-predict-model)
  
2. **Second Model: Tumor Localization**

   - **Description:** This model detects the location of the tumor within the MRI scan.
   - **Link:** [Second Model](https://www.kaggle.com/code/abdelrahmankamel/bt-seg-model)

3. **Third Model: Tumor Type Classification**

   - **Description:** This model classifies the type of tumor present in the MRI scan.
   - **Link:** [Third Model](https://www.kaggle.com/code/abdelrahmankamel/type-predict)
  
## Datasets
1. **Dataset 1 : Brain Tumor Dataset**

   - **Description:** A dataset containing MRI scans for training the tumor detection models.
   - **Link:** [Dataset 1](https://www.kaggle.com/datasets/abdelrahmankamel/btdataset)

2. **Dataset 2 : Tumor Types Dataset**
   - **Description:** A dataset used for classifying tumor types.
   - **Link:** [Dataset 2](https://www.kaggle.com/datasets/abdelrahmankamel/tumor-types)


## Installation
To set up the project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Abdelrahman-Kamel8886/Brain-Tumor-Detection-FastApi.git
   cd Brain-Tumor-Detection-FastApi

3. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

4. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt

4. **Run the Application:**
   ```bash
   uvicorn main:app --reload

Access the web application at http://127.0.0.1:8000.

## Usage
1. Open the application in your web browser.
2. Use the provided interface to upload an MRI scan.
3. The models will analyze the scan and display results regarding tumor presence, location, and type.
   
## Configuration
- **Model Path:** The pre-trained model files should be placed in the models directory.
- **Environment Variables:** Set any required environment variables in a .env file for configuration.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.


## Acknowledgements

- **FastAPI:** A modern, fast (high-performance) web framework for building APIs with Python 3.7+.
- **Deep Learning Models:** Pre-trained models for various aspects of brain tumor detection.
- **Datasets:** Essential for training and evaluating the models.


## Team Memebrs
For any questions or inquiries, please contact:

- ### Abdelrahman Kamel
  - **LinkedIn: [LinkedIn Profile](www.linkedin.com/in/abdelrahman-kamel-7a7457200)**
  - **Email: abdelrahmankamel8886@gmail.com**
- ### Mostafa Adel
- ### Ahmed Abdelhakim
- ### Tarek Awady
- ### Ahmed Hamdy
- ### Mostafa Mahdy








