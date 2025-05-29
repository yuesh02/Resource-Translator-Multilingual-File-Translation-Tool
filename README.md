---

# 🌐 Resource Translator – Multilingual File Translation Tool

This project is a desktop-based **file translation utility** that allows users to upload and translate **Images, PDFs, Word Documents, and Text Files** into multiple languages. It uses OCR (Tesseract), Google Translate API, and a simple **Tkinter GUI** for interaction.

---

## ✨ Features

* 📄 Translate PDF, DOCX, TXT files
* 🖼️ Extract and translate text from images (using OCR)
* 🌍 Support for multiple languages (English, Hindi, French, etc.)
* 💾 Save/download translated content
* 🧠 Intelligent handling of file types with automatic detection

---

## 🛠️ Tech Stack

* Python
* Tkinter (GUI)
* [pytesseract](https://github.com/madmaze/pytesseract) for OCR
* [python-docx](https://python-docx.readthedocs.io/) for Word file handling
* [PyMuPDF](https://pymupdf.readthedocs.io/) (fitz) for PDF extraction
* [googletrans](https://py-googletrans.readthedocs.io/) for translation
* [pdf2docx](https://pypi.org/project/pdf2docx/) (for optional conversion)

---

## 📥 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/resource-translator.git
cd resource-translator
```

### 2. Install Required Libraries

```bash
pip install pytesseract Pillow googletrans==4.0.0-rc1 python-docx PyMuPDF pdf2docx
```

> 🔍 **Note:** You must also install [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) on your system and add it to your PATH.

---

## 🚀 Usage

1. **Run the App**

```bash
python translator_app.py
```

2. **Steps in GUI**:

   * Click **Open File** to upload a resource.
   * Select the **Target Language** (e.g., Hindi, French).
   * Choose the **Resource Type** (Image, PDF, DOCX, or TXT).
   * Click **Translate**.
   * Save the translated file when prompted.

---

## 🌍 Supported Languages

* English (`en`)
* Spanish (`es`)
* French (`fr`)
* Hindi (`hi`)
* Marathi (`mr`)
* Bengali (`bn`)
* Gujarati (`gu`)
* Tamil (`ta`)
* Telugu (`te`)

> Easily extend by adding more languages to the `target_languages` dictionary.

---

## 📁 Project Structure

```
resource-translator/
├── translator_app.py          # Main GUI application
├── requirements.txt           # Optional: list of dependencies
└── README.md                  # Project documentation
```

---

## ✅ Future Enhancements

* Language auto-detection
* Support for DOC (legacy Word) and Excel files
* Batch processing of multiple files
* Dark mode for GUI

---

## 👤 Author

**Yujesh Shyam**
Aspiring developer | Backend & AI enthusiast
📫 Reach out for collaboration!

---

