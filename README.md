# Image-Converter
Sure! Here's a detailed and polished `README.md` content for your **Image Converter GUI** project on GitHub:

---

# 🖼️ Image Converter GUI (Python + Tkinter)

A simple and efficient **Image Converter Application** built with **Python**, featuring a **Tkinter GUI** for ease of use. It allows users to convert images between various formats (JPG, PNG, BMP, GIF, etc.) with additional functionality like batch processing, resizing, and compression.

---

## ✨ Features

- ✅ **Graphical User Interface (GUI)** built with Tkinter
- ✅ **Format Conversion**: Convert images to JPG, PNG, BMP, GIF
- ✅ **Batch Processing**: Convert multiple images at once
- ✅ **Image Resizing**: Optionally resize images before saving
- ✅ **JPEG Compression**: Adjust image quality during conversion
- ✅ **Error Handling**: Skips unsupported or corrupted files with error messages
- ✅ **Output Folder Selection**: Choose where to save the converted images

---

## 📷 Supported Formats

- Input: `.jpg`, `.jpeg`, `.png`, `.bmp`, `.gif`
- Output: `.jpg`, `.png`, `.bmp`, `.gif`

---

## 🚀 How to Run

### 1. **Install Dependencies**

```bash
pip install pillow opencv-python
```

### 2. **Run the Application**

```bash
python image_converter.py
```

> A GUI window will open where you can select images, choose the output format, resize them, and convert with just a few clicks.

---

## 📋 Usage Instructions

1. **Select Images**: Choose one or more images to convert.
2. **Choose Format**: Select the desired output format (JPG, PNG, etc.).
3. **Resize (Optional)**: Enter a new width and height for resizing (leave blank to keep original size).
4. **JPEG Compression**: Enable if converting to JPG (quality set to 85 by default).
5. **Output Folder**: Choose where to save the converted files.
6. **Convert**: Click the “Convert” button to start batch conversion.

---

## 💡 Example Use Case

Convert 10 PNG images to compressed 800x600 JPGs:

1. Select 10 PNGs from your folder
2. Set output format to `JPG`
3. Enter `800` (width) and `600` (height)
4. Enable JPEG Compression
5. Choose your output folder
6. Click `Convert`

---

## 🛠️ Technologies Used

- **Python 3.7+**
- **Pillow (PIL Fork)** – for image processing
- **OpenCV** – optional, can be integrated for advanced features
- **Tkinter** – for GUI

---

## 🧩 Future Improvements

- Add drag-and-drop support
- Integrate image preview before and after conversion
- Add support for additional formats (e.g., TIFF, WebP)
- Multi-threading for faster processing
- Dark/light mode for GUI

---
