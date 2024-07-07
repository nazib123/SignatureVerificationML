# Signature Verification using Machine Learning


## Overview

This project demonstrates the application of statistical analysis and predictive modeling using various machine learning algorithms to verify signatures.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Implementation](#implementation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

Signature verification is a critical task in various fields such as banking, legal documents, and identity verification. This project aims to build a machine learning model that can accurately verify signatures by analyzing their statistical features and applying predictive modeling techniques.

## Dataset

The dataset used for this project includes a collection of genuine and forged signatures. Each signature is processed to extract relevant features such as shape, texture, and geometric properties.

## Methodology

The methodology for this project involves the following steps:
1. Data Collection: Gathering genuine and forged signature samples.
2. Preprocessing: Cleaning and normalizing the signature data.
3. Feature Extraction: Extracting statistical and geometric features from the signatures.
4. Model Training: Training machine learning models using the extracted features.
5. Model Evaluation: Evaluating the performance of the trained models using various metrics.

## Implementation

The implementation of the signature verification model includes:
1. Data preprocessing using Python libraries.
2. Feature extraction using techniques such as Histogram of Oriented Gradients (HOG) and Scale-Invariant Feature Transform (SIFT).
3. Model training using machine learning algorithms like Support Vector Machines (SVM), Random Forest, and Neural Networks.
4. Model evaluation using metrics such as accuracy, precision, recall, and F1-score.

## Results

The results of the project demonstrate the effectiveness of the machine learning models in verifying signatures. The models achieved high accuracy and were able to distinguish between genuine and forged signatures with a significant level of precision.

## Conclusion

This project successfully demonstrates the application of machine learning in signature verification. The developed models can be further improved and integrated into real-world applications to enhance security and authentication processes.

## Installation

To get a local copy up and running, follow these simple steps:

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/SignatureVerificationML.git
   cd SignatureVerificationML
   Install dependencies

2. **Install dependencies**
      ```bash
      pip install -r requirements.txt

## Usage
1. Use jupiter notebook to run the application

2. **Using the application**
Run it in the Jupyter notebook and use your own PDF file. Please carefully review the following preparation instructions.
- Each PDF file should contain 8 signatures, each placed within a separate square box.The signatures should be handwritten. Print the PDF, then scan the printed pages.
- Each PDF file should contain 8-10 pages, with each page featuring slight variations of one person's signature. 
- There will be a total of 9 different PDFs, each showcasing the signatures of 9 different individuals.
![signature PDF format](https://github.com/nazib123/SignatureVerificationML/assets/137222846/c0022d9e-f1d5-4904-8527-7e863f8bec45)


## Features

- Verify signatures using machine learning models.
- Analyze statistical features of signatures.
- Utilize various machine learning algorithms for predictive modeling.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

1. **Fork the Project**
2. **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the Branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

## License

Distributed under the MIT License. See LICENSE for more information.

## Contact

Sk. Nazib Ahmed - [sheikhnazib@gmail.com](mailto:sheikhnazib@gmail.com)

