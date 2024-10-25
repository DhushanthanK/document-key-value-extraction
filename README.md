# Document OCR Key-Value Extraction

This repository contains a Python-based project for extracting and validating key-value pairs from OCR (Optical Character Recognition) data using custom logic and PaddleOCR KIE (Key Information Extraction). The project aims to compare the accuracy and performance of both approaches.

## Features

- Extracts key-value pairs from financial documents (e.g., account statements).
- Validates extracted data using custom validation logic.
- Compares the performance and accuracy of custom extraction logic and PaddleOCR's KIE model.
- Uses regular expressions to validate different types of data (e.g., dates, monetary amounts).

## Technologies

- **Python**
- **PaddleOCR** (for OCR and KIE)
- **Fuzzy Matching** (via `fuzzywuzzy` for key-value extraction)
- **Regular Expressions** (for validation)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/document-ocr-extraction.git
    ```
2. Navigate to the repository folder:
    ```bash
    cd document-ocr-extraction
    ```
3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Comparison with PaddleOCR KIE

This project also includes a comparison of custom logic vs. PaddleOCR’s KIE system. Custom logic tends to perform better with structured documents, whereas PaddleOCR KIE is more versatile with unstructured layouts.

## License

This project is licensed under the MIT License.
