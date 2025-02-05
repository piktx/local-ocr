<p align="center"><h1 align="center">🦙 Llama OCR - Image Text Extraction Tool</h1></p>
<p align="center">
	<em>Privacy-focused OCR using Llama 3.2 Vision</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/languages/top/piktx/local-ocr" alt="repo-top-language">
	<img src="https://img.shields.io/badge/python-3.9%2B-blue" alt="python-version">
</p>
<br>

## 🔗 Table of Contents

- [📍 Overview](#-overview)
- [👾 Features](#-features)
- [📁 Project Structure](#-project-structure)
  - [📂 Project Index](#-project-index)
- [🚀 Getting Started](#-getting-started)
   - [Prerequisites](#-prerequisites)
  - [Installation](#-installation)
  - [Usage](#-usage)

---

## 📍 Overview

**LOCAL-OCR** is a privacy-first optical character recognition tool that leverages the Llama 3.2 Vision model for local text extraction from images. Designed for users who need offline capabilities and data privacy, it features:

- 🛡️ 100% local processing (no cloud dependencies)
- 🖼️ Support for common image formats (PNG/JPG/JPEG)
- 📊 Streamlit-powered web interface
- 🧹 One-click results cleanup
- 📝 Structured Markdown output formatting

---

## 👾 Features

- **Local Processing**: Runs entirely on your machine without internet connection
- **AI-Powered Extraction**: Utilizes Llama 3.2 Vision for superior text recognition
- **Markdown Formatting**: Presents results in organized markdown format
- **Image Preview**: Displays uploaded images in sidebar
- **Responsive UI**: Clean and intuitive web interface
- **Privacy Focused**: No data leaves your local machine

---

## 📁 Project Structure

```sh
└── local-ocr/
    ├── README.md
    ├── app.py
    └── requirements.txt
```

---
## 🚀 Getting Started

### ☑️ Prerequisites

Before getting started with local-ocr, ensure your runtime environment meets the following requirements:

- **Programming Language:** Python
- **Ollma installations:**

  ```sh
  curl -fsSL https://ollama.ai/install.sh | sh
  ```
- **Download Llama 3.2 Vision model:**
  ```sh
  ollama pull llama3.2-vision

### ⚙️ Installation

Install local-ocr using the following method:

1. Clone the local-ocr repository:
```sh
git clone https://github.com/piktx/local-ocr
```

2. Navigate to the project directory:
```sh
cd local-ocr
```

3. Install the project dependencies:
```sh
pip install -r requirements.txt
```



### 🤖 Usage
Run local-ocr using the following command:
```sh
streamlit run local-ocr.py
```
