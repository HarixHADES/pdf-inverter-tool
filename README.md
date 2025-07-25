# 🧾 PDF Inverter Tool (Colour ↔ Black & White)

A simple Python GUI tool that allows users to invert black and white in up to 5 PDF files. The processed PDFs are saved in a user-selected output folder. Built using `tkinter`, `pdf2image`, and `Pillow`.

---

## 📌 Features

- Select **up to 5 PDF files** at once
- Invert black and white content (pure binary)
- Choose a **custom output folder**
- Lightweight and easy-to-use GUI
- Optionally compile into a standalone `.exe` file using PyInstaller

---

## 🛠️ Requirements

- Python 3.x
- [Poppler](https://github.com/oschwartz10612/poppler-windows/releases) (must be added to PATH)

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/HarixHADES/pdf-inverter-tool.git
   cd pdf-inverter-tool
2.Install dependencies:
 ```bash
pip install -r requirements.txt

## 🚀 How to Use
1.Run the script:

bash
python invert_gui.py

2.Click “Choose up to 5 PDFs” and select your files.

3.Click “Generate Inverted PDFs”.

4.Choose an output folder.

5.The inverted PDFs will be saved there.


