# Organising Medical Documentation with ICD-10 Codes

This project leverages machine learning and **natural language processing (NLP)** to extract key medical information from transcriptions and match it with ICD-10 codes. It aims to automate and streamline the process of organising medical documentation for efficient diagnosis and billing.

## Key Features

- Data Cleaning and Preprocessing: Handles raw medical transcription data, preparing it for analysis.
- NLP Techniques: Uses advanced models to extract relevant details, such as patient age, symptoms, diagnoses, and treatments.
- ICD-10 Mapping: Automates the matching of extracted data with appropriate ICD-10 codes for standardisation.
- Output Generation: Produces a structured DataFrame summarising key insights, including:
  - Patient age
  - Recommended treatments
  - Medical specialty
  - Matched ICD-10 codes

## Environment Setup

To ensure the project runs smoothly, create a `.env` file in the project root using the provided `.env.example` as a template to use your own OpenAI API key. This key is necessary for accessing the OpenAI API to perform text analysis and mapping tasks.

## How to Use

1. Clone this repository and navigate to the project directory.
2. Install dependencies:

```bash
Copy code
pip install -r requirements.txt
```

3. Set up the .env file as described above.
4. Run the Jupyter Notebook:

```bash
jupyter notebook organising-medical-docs.ipynb
```

5. Follow the steps in the notebook to load data, preprocess it, and generate structured outputs.
