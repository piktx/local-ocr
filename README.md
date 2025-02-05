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
- [🚀 Getting Started](#-getting-started)
   - [Prerequisites](#%EF%B8%8F-prerequisites)
  - [Installation](#%EF%B8%8F-installation)
  - [Usage](#-usage)
- [🔰 Contributing](#-contributing)

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
<a name="prerequisites"></a>
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
<a name="installation"></a>
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
---
## 🔰 Contributing

- **💬 [Join the Discussions](https://github.com/piktx/local-ocr/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/piktx/local-ocr/issues)**: Submit bugs found or log feature requests for the `local-ocr` project.
- **💡 [Submit Pull Requests](https://github.com/piktx/local-ocr/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.


### Contributing Guidelines

1. **Fork the Repository**: Start by forking the project repository to your github account.

2. **Clone Locally**: Clone the forked repository to your local machine using a git client.

   ```sh
   git clone https://github.com/piktx/local-ocr
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!


---
