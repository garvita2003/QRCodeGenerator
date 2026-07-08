# QRCode Generator 🔳

## 📌 Introduction

**QRCode Generator** is a simple Python utility that creates a QR code from a text string or URL and saves it in both SVG and PNG formats. The current script uses a hardcoded GitHub profile link and generates the output with the `pyqrcode` library.

**Key Features:**
- ✅ Generates a QR code from a text string or URL
- ✅ Uses a hardcoded GitHub profile link as input
- ✅ Creates QR output using the `pyqrcode` library
- ✅ Saves the generated QR code as an SVG file
- ✅ Saves the generated QR code as a PNG file
- ✅ Allows easy replacement of the input string for custom QR codes
- ✅ Lightweight command-line Python script

---

## 🔄 Process / Flow

**User Interaction Flow:**
1. User opens the Python script
2. A string value is defined in the variable `s`
3. The script passes that string to `pyqrcode.create()`
4. A QR code object is generated from the input value
5. The script exports the QR code as `myqr.svg`
6. The script exports the QR code as `myqr.png`
7. User can open or share the generated files

**Generated Output:**
1. **SVG Output**: Vector QR image saved as `myqr.svg`
2. **PNG Output**: Raster QR image saved as `myqr.png`

---

## 🛠️ Technology Used

| Component | Technology |
|-----------|-----------|
| **Programming Language** | Python |
| **QR Code Library** | `pyqrcode` |
| **PNG Support** | `pypng` |
| **Image Support** | Pillow |
| **Application Type** | Command-line QR code generator |
| **Output Formats** | SVG and PNG |

---

## 🎓 Skills Gained

**Python Programming:**
- ✅ Writing simple script-based automation
- ✅ Importing external libraries into Python projects
- ✅ Working with string variables as input data
- ✅ Saving generated files from code

**QR Code Generation:**
- ✅ Creating QR codes from text or URLs
- ✅ Using `pyqrcode.create()` to generate QR objects
- ✅ Exporting one QR code into multiple file formats
- ✅ Understanding basic QR code generation workflows

**File Output Handling:**
- ✅ Saving SVG files programmatically
- ✅ Saving PNG files programmatically
- ✅ Managing named output assets from a Python script

**Project Design:**
- ✅ Building a minimal utility project with clear input and output
- ✅ Keeping the logic simple and reusable for future customization
- ✅ Understanding how to adapt scripts for personal tools or automation

---

## 📂 Project Structure

```
QRCodeGenerator-main/
└── QRCodeGenerator-main/
    ├── code.py                # Main script for generating QR codes
    └── README.md              # Project documentation
```

---

## 📸 Demonstration

**What the Script Produces:**
- Generates a QR code from the URL stored in the script
- Saves a vector version as `myqr.svg`
- Saves an image version as `myqr.png`

---

## ⚙️ Setup Instructions

### Prerequisites:
- Python 3 installed
- Any terminal or code editor such as VS Code

### Step-by-Step Installation:

**1. Clone the Repository**
```bash
git clone <repository-url>
cd QRCodeGenerator-main/QRCodeGenerator-main
```

**2. Install Dependencies**
```bash
pip install pyqrcode
pip install Pillow
pip install pypng
```

**3. Run the Application**
```bash
python code.py
```

**4. View the Result**
- Check the project folder for `myqr.svg`
- Check the project folder for `myqr.png`

**5. Customize the QR Content**
```python
# In code.py
s = "https://github.com/garvita2003/"
```
Replace the string with any website link or text value you want to encode into a QR code.
