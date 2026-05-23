# 📝 Dpad Text Editor

---
## 🎨 Screenshots

---
![Light Theme]

<img width="897" height="499" alt="d1" src="https://github.com/user-attachments/assets/0c9f7711-928c-48cb-84d5-7f78e3e32473" />

![Monokai Theme]

<img width="898" height="499" alt="d2" src="https://github.com/user-attachments/assets/d1584760-6e11-4ad4-a9f2-c0b8cd193328" />

## ✨ Features

- **Font Customization** — Change font family and size from the toolbar
- **Text Formatting** — Bold, Italic, and Underline support
- **Font Color Picker** — Choose any custom color for your text
- **Text Alignment** — Left, Center, and Right alignment
- **Find & Replace** — Search and replace words instantly with highlighted matches
- **6 Built-in Color Themes:**

| Theme | Background |
|-------|-----------|
| Light Default | White |
| Light Plus | Light Gray |
| Dark | Dark Gray |
| Red | Soft Red |
| Monokai | Gold |
| Night Blue | Steel Blue |

- **File Operations** — New, Open, Save, Save As with unsaved-changes warning
- **Live Status Bar** — Real-time word and character count
- **Toggle UI** — Show/hide toolbar and status bar from View menu
- **Keyboard Shortcuts** — Full hotkey support for faster workflow

---

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| New File | `Ctrl + N` |
| Open File | `Ctrl + O` |
| Save | `Ctrl + S` |
| Save As | `Ctrl + Alt + S` |
| Exit | `Ctrl + Q` |
| Find | `Ctrl + F` |
| Copy | `Ctrl + C` |
| Paste | `Ctrl + V` |
| Cut | `Ctrl + X` |
| Clear All | `Ctrl + Alt + X` |

---

## 🛠️ Requirements

- Python 3.x
- Tkinter *(comes pre-installed with Python)*

No additional pip packages needed to run the source!

---

## 🚀 Getting Started

### Run from Source

```bash
git clone https://github.com/your-username/dpad-text-editor.git
cd dpad-text-editor
python Dpad.py
```

> Make sure `icons2/` folder and `icon.ico` are in the same directory as `Dpad.py`

---

## 📦 Build as Windows Executable

This project uses **cx_Freeze** to build a standalone `.exe`.

### 1. Install cx_Freeze
```bash
pip install cx_Freeze
```

### 2. Update TCL/TK paths in `setup.py`
```python
os.environ['TCL_LIBRARY'] = r"C:\path\to\Python\tcl\tcl8.6"
os.environ['TK_LIBRARY'] = r"C:\path\to\Python\tcl\tk8.6"
```

### 3. Build
```bash
python setup.py build
```

The executable will be generated in the `build/` folder.

---

## 📁 Project Structure

```
Dpad-text-editor/
│
├── build/           # Compiled output
├── dist/            # Installer (.msi)
├── icons2/          # Toolbar & menu icons
├── Dpad.py          # Main application
├── setup.py         # cx_Freeze build config
├── icon.ico         # App icon
├── tcl86t.dll       # Required for exe build
├── tk86t.dll        # Required for exe build
└── README.md
```



