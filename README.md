# Handwriting Recognition App

This project consists of a React frontend and a Python Flask backend for handwriting recognition.

## Prerequisites

- Node.js (v18+)
- Python (v3.8+)

## Setup Instructions

### 1. Backend Setup

Navigate to the `backend` directory and install the required Python packages.

```bash
cd backend
pip install -r requirements.txt
```

**Note:** The backend uses `easyocr` which will download models to the `backend/models` directory on the first run. This ensures compatibility and avoids version conflicts.

### 2. Frontend Setup

Navigate to the root directory (or open a new terminal) and install the Node.js dependencies.

```bash
npm install
```

## Running the Application

### 1. Start the Backend Server

In the `backend` directory, run:

```bash
python app.py
```

The server will start at `http://localhost:5000`.

### 2. Start the Frontend Development Server

In the root directory, run:

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the port shown in the terminal).

## Usage

1. Open the application in your browser.
2. Upload an image containing handwriting.
3. Select the language (English or Tamil).
4. Click "Convert" to see the recognized text.
