# Spammer Detection and Fake User Identification on Social Networks

This repository contains the source code and project report for a system designed to detect spammers and fake users on Twitter. The project utilizes various machine learning algorithms, with a focus on the Extreme Learning Machine (ELM) for its computational efficiency.

## Project Files

- `SpamDetection.py`: The Python source code for the application.
- `documentation.pdf`: The full project report detailing the system's design, methodology, and results.

## Key Features

* **Twitter Data Processing**: The application can process Twitter data in JSON format, extracting features like retweet count, follower/following ratios, and tweet content.
* **Machine Learning Models**: It compares the performance of several machine learning algorithms, including:
    * Random Forest
    * Naive Bayes
    * Support Vector Machine (SVM)
    * Extreme Learning Machine (ELM)
* **Performance Metrics**: The system calculates and displays accuracy, precision, recall, and F-measure for each algorithm.
* **User Interface**: A graphical user interface (GUI) is included for easy interaction, allowing users to upload datasets and run detection algorithms with a few clicks.

## How It Works

The system follows a multi-step process:

1.  **Data Upload**: A user uploads a folder containing Twitter data in JSON format.
2.  **Feature Extraction**: The application extracts features from each tweet and user account. Naive Bayes is used for text-based feature extraction from tweet content.
3.  **Model Training & Prediction**: The extracted features are used to train and test different machine learning classifiers to identify fake accounts and spam content.
4.  **Results & Visualization**: The results, including algorithm performance metrics and a detection graph, are displayed.

## Getting Started

To run the project, you need Python and several libraries. Refer to the project report (`document.11(2).pdf`) for detailed system and software requirements.

## Credits

This project was developed by:
* Amireddy Madhuvika 
* Pantula Sanathan
* Rampally Navaneeth 
