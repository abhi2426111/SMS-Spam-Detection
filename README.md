# SMS-Spam-Detection
## Overview

This project is a **real-time SMS Spam Detection** system that uses **Natural Language Processing (NLP)** and **Machine Learning** to classify SMS messages as spam or not spam. It is built using **Python**, **scikit-learn**, and **pandas**.

## Features

- Preprocesses SMS messages by removing punctuation and numbers.
- Uses **TF-IDF Vectorization** to convert text into numerical features.
- Trains a **Naïve Bayes classifier** for spam detection.
- Allows the user to input an SMS message for real-time prediction.
- Saves the trained model using **pickle** for later use.

## Installation

1. Clone the repository or download the script.
2. Install the required dependencies using:
3. Place the `spam.csv` dataset in the project directory.

## Usage

Run the script using:

Enter an SMS message when prompted, and the program will predict whether it is **Spam** or **Not Spam**.

## Dataset

The script expects a CSV file (`spam.csv`) with two columns:

- `v1`: Label (`ham` for non-spam, `spam` for spam)
- `v2`: Message content

## Model Training

The model follows these steps:

1. Load and clean the dataset.
2. Apply **TF-IDF Vectorization** to convert text to numerical format.
3. Train a **Multinomial Naïve Bayes model**.
4. Evaluate accuracy on a test set.
5. Save the trained model as `spam_detector.pkl`.

## Example Output

## Future Enhancements

- Deploy as a **Flask API** for real-time detection.
- Improve accuracy with **Deep Learning** models.
- Integrate with an SMS service like **Twilio** for automatic spam filtering.

## License

This project is open-source and available for modification and redistribution.
