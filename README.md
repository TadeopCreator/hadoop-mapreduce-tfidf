# Hadoop MapReduce TF-IDF

This repository contains Python code implementing TF-IDF (Term Frequency-Inverse Document Frequency) using Hadoop's MapReduce framework. TF-IDF is a fundamental technique in information retrieval and text mining.

## Overview

The project involves multiple MapReduce jobs:

- **Job Cleaner**: Cleans the text data by removing unwanted characters and combines text fragments for each document.
- **Job TF**: Calculates the TF (Term Frequency) of words in each document.
- **Job D**: Computes the total count of processed documents.
- **Job TF-IDF**: Calculates the TF-IDF value for each term in the document collection.

## Project Structure

- `input/`: Directory containing input data.
- `output/`: Directory to store job outputs.
- `MRE.py`: Module containing job definitions and logic.

## Running the Code

1. Set up your Hadoop environment for example on Google Colab.
2. Adjust the paths in the code (`root_path`, `inputDir`, `outputDir`) to match your environment.
3. Execute the jobs in sequence as described in the code comments.

## DAG Diagram

![DAG Diagram](https://github.com/TadeopCreator/hadoop-mapreduce-tfidf/blob/main/images/DAG-tf-idf.jpg)

Feel free to explore the code to understand each job's functionality and adapt it as needed for your use case.
