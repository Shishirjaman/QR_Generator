# 🚀 Text-to-QR Code Converter

A full-stack web application that generates QR codes from user-provided text. This project uses a **FastAPI** (Python) backend for image generation and a **React + Vite** (JavaScript) frontend for a responsive user interface.

## 🛠 Tech Stack

- **Frontend:** React, Vite, Bootstrap
- **Backend:** FastAPI, Uvicorn, Python-QRCode, Pillow
- **Communication:** REST API (JSON)

## 📦 Features

- Real-time QR code generation.
- Base64 image encoding for fast delivery.
- Error handling for empty inputs.
- Loading states for a better user experience.
- Responsive design using Bootstrap.

---

## 🚀 Getting Started

### 1. Prerequisites
- Node.js installed
- Python 3.8+ installed

### 2. Backend Setup (FastAPI)
1. Navigate to the project root.
2. Create and activate a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
