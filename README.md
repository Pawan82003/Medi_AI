# 🧠 MediGrid AI – Personal Prescription Assistant

## 📌 Overview

**MediGrid AI** is an intelligent healthcare assistant designed to simplify the process of managing handwritten prescriptions. It leverages AI to extract, analyze, and organize prescription data while enhancing patient safety and convenience.

The application focuses on three key pillars:

* ⚡ **Speed** – Quickly digitizes handwritten prescriptions
* 🛡️ **Safety** – Detects potential drug interactions and warnings
* 📍 **Convenience** – Helps locate nearby pharmacies with required medicines

### Run Command
python -m uvicorn fast_api_file:api --reload --reload-exclude "*.db"
---

## 🚀 Key Features

### 🔍 Smart Prescription Analysis

* Extracts medication details from handwritten prescriptions
* Identifies:

  * Medicine names
  * Dosage
  * Frequency
  * Duration

### ⚠️ Safety & Drug Interaction Checks

* Detects potential drug interactions
* Provides safety warnings and recommendations

### 📍 Pharmacy Locator

* Uses user location to find nearby pharmacies
* Provides direct Google Maps navigation links

---

## ⚙️ How It Works

The application follows a simple 3-step workflow:

1. **Enable Location**

   * Click the *Location Service* button in the sidebar
   * Required to find nearby pharmacies

2. **Upload Prescription**

   * Upload a clear image of the prescription
   * Supports drag-and-drop functionality

3. **View Results**

   * Explore extracted data and insights
   * Navigate to pharmacies directly from the app

---

## 🖥️ Application Interface

### 📌 Sidebar (Control Panel)

* **Location Service** – Enables location access (mandatory)
* **User Guide** – Quick instructions for users
* **Settings**

  * Confidence Threshold (50%–100%) for AI accuracy

---

### 📌 Main Screen

* **File Uploader** – Upload prescription image
* **Uploaded Document Preview** – View uploaded image
* **View History** – Access previously saved records
* **Analysis Results Panel** – Displays extracted data and warnings

---

## 📊 Results & Insights

### 📋 Extracted Data

* Displays structured prescription data in table format
* Includes **Pharmacy Location links** for each medicine
* Direct navigation to nearby pharmacies via Google Maps

---

### ⚠️ Critical Warnings

* Highlights:

  * Drug interactions
  * Safety alerts
* Helps users make informed decisions

---

## 💾 Additional Actions

* **Download Report** – Export analyzed data
* **Save to Database** – Store patient and prescription history

---

## 🤖 AI Assistant Guidance

### ▶️ Getting Started

**User:** "How do I use this app?"
**Response:**
"Just follow three steps:

1. Enable Location
2. Upload your prescription
3. Check the Extracted Data tab for results"

---

### 🛠️ Troubleshooting

**User:** "Analysis isn’t starting"
**Response:**
"Please check:

1. Location is enabled
2. A clear prescription image is uploaded"

---

### 📍 Finding Medicines

**User:** "Where can I buy my medicine?"
**Response:**
"Go to the Extracted Data tab and click the *View Map* link next to your medicine."

---

### ⚠️ Safety Information

**User:** "What about side effects?"
**Response:**
"Check the Critical Warnings tab. Always confirm with a doctor or pharmacist."

---

## ⚠️ Disclaimer

This application provides AI-generated insights for informational purposes only.
It is **not a substitute for professional medical advice**. Always consult a qualified healthcare provider.

