# 🔍 Local Image Text Extractor

A fast, lightweight, and 100% client-side Web App that extracts text from images directly in your browser. Powered by **Tesseract.js** (WebAssembly OCR) and **Cropper.js**, your data never leaves your device—providing total privacy with zero server uploads.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Client-Side Only](https://img.shields.io/badge/privacy-100%25%20client--side-brightgreen)
![Tech Stack](https://img.shields.io/badge/tech-HTML5%20%7C%20TailwindCSS%20%7C%20JS-orange)

---

## ✨ Features

* 🔒 **100% Local & Private:** All Optical Character Recognition (OCR) takes place locally using WebAssembly. No data or images are sent to external servers.
* ✂️ **Image Editing & Region Selection (ROI):** Rotate, zoom, and select specific sub-regions of an image to increase recognition accuracy.
* 🌍 **Multi-Language Support:** Recognizes text in English, French, Spanish, German, Chinese, Japanese, Russian, Portuguese, Italian, and Arabic.
* 📊 **Real-Time Extraction Progress:** Visual loading bars and percentage feedback during image processing.
* 📝 **Extracted Text Utilities:**
  * One-click **Copy to Clipboard**.
  * Instant **`.txt` File Download**.
  * Live **Text Search & Highlight**.
  * Statistics bar showing word count, character count, and engine confidence scores.
* 🌓 **Dark & Light Mode Support:** Clean, modern responsive interface designed with Tailwind CSS and Lucide Icons.

---

## 🛠️ Tech Stack

* **OCR Engine:** [Tesseract.js](https://tesseract.projectnaptha.com/) (JavaScript port of Tesseract OCR via WebAssembly)
* **Image Crop / ROI:** [Cropper.js](https://fengyuanchen.github.io/cropperjs/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **Icons:** [Lucide Icons](https://lucide.dev/)

---
