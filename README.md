# NLP Lab 4 (L029)

This repository contains a Jupyter Notebook demonstrating practical applications of **Python libraries** for **web scraping** and **optical character recognition (OCR)**.

## 📌 Contents

* `NLP_LAB4_L029.ipynb` — Jupyter notebook with code, explanations, and observations.

## 🚀 Features

1. **Web Scraping with BeautifulSoup & Requests**

   * Extracts product details (title, price, rating) from Amazon listings.
   * Implements custom headers to mimic browser requests and bypass anti-scraping measures.
   * Includes error handling for failed requests or structural changes in the target website.

2. **OCR with Pytesseract & Pillow**

   * Recognizes and extracts text from images.
   * Requires **Tesseract OCR** installed on the system.
   * Uses `pytesseract.image_to_string()` for text recognition.

## 🛠️ Requirements

Install dependencies before running the notebook:

```bash
pip install requests beautifulsoup4 pillow pytesseract
```

Additionally, install **Tesseract OCR**:

* **Windows**: Download from [Tesseract at UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki)
* **Linux (Ubuntu/Debian)**:

  ```bash
  sudo apt-get install tesseract-ocr
  ```
* **macOS (Homebrew)**:

  ```bash
  brew install tesseract
  ```

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/NLP_LAB4_L029.git
   cd NLP_LAB4_L029
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook NLP_LAB4_L029.ipynb
   ```
3. Run the cells step by step to see scraping and OCR results.

## 📖 Learnings

* **Web scraping** allows automated data extraction from websites using Python.
* **OCR** converts text in images into machine-readable format.
* Both tasks showcase how specialized libraries extend Python’s capabilities for **data collection** and **processing**.

## ✅ Conclusion

This lab demonstrates how Python can be applied to real-world **data acquisition** tasks, from scraping structured web data to recognizing unstructured text in images.

Would you like me to also add **sample outputs/screenshots** (like scraped data table or OCR result) to make the README more engaging for GitHub?
