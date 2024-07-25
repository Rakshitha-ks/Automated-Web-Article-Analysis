# Automated Web Article Extraction, Sentiment Analysis, and Readability Scoring Using Python

## Overview

_This project is designed to automate the extraction, processing, and analysis of web articles. The primary focus is to perform sentiment analysis and readability scoring on the content fetched from various web pages. The project utilizes Python and various libraries such as BeautifulSoup, NLTK, and pandas to accomplish these tasks._

## Table of Contents

1. [Introduction](#Introduction)
2. [Features](#Features)
3. [Installation](#Installation)
4. [Usage](#Usage)
5. [Project Structure](#ProjectStructure)
   

## Introduction

In this project, we automate the process of extracting articles from web pages, cleaning the extracted text, and analyzing the sentiment and readability of the content. This can be particularly useful for researchers, data scientists, and content analysts who need to process and analyze large volumes of textual data.

## Features

- ***Web Article Extraction:*** Fetch articles from given URLs.
- ***Content Cleaning:*** Remove stopwords and irrelevant content from the extracted text.
- ***Sentiment Analysis:*** Calculate positive, negative, polarity, and subjectivity scores of the text.
- ***Readability Metrics:*** Compute various readability metrics such as average sentence length, fog index, and word count.
- ***Automated Report Generation:*** Save the analysis results into a CSV file for further use.

## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Clone the Repository

```
git clone https://github.com/your-username/Automated-Web-Article-Analysis.git
cd Automated-Web-Article-Analysis
```

## Usage

1. **Prepare Your CSV File:** Ensure you have a CSV file with URLs of the articles you want to analyze  [Input.csv] . Place this file in the root directory of the project. 

2. **Run the Script:** Execute the main script [Automated Web Article Analysis and Sentiment Scoring.ipynb] to start the extraction and analysis process.

3. **View the Results:** The analysis results will be saved in a CSV file named Output.csv in the root directory.

***Example Usage***

```
python main.py --input "path_to_your_input_csv.csv" --output "path_to_your_output_csv.csv"
```

## ProjectStructure

- ***Automated Web Article Analysis and Sentiment Scoring.ipynb:*** The main script to run the entire process.
- ***Text Analysis.docx:*** Contains the objectives of this project.
- ***StopWords:*** Contains stop words lists.
- ***MasterDictionary:*** Dictionary of Positive and Negative words.
- ***Input.csv:*** CSV file used for data extraction.
- ***Output.csv:*** Stores the data analysis output.


