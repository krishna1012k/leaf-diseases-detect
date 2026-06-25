

# README.md

## 🌿 AI Leaf Disease Detection System

An AI-powered plant health monitoring system that detects leaf diseases from uploaded images using **Groq Llama Vision**, assesses disease severity, and provides actionable treatment recommendations. The application helps farmers, gardeners, and agricultural professionals identify plant diseases quickly and accurately.

## 🚀 Features

* 📸 Upload leaf images for analysis
* 🤖 AI-powered disease detection using Llama Vision
* 🔍 Identification of multiple plant diseases
* 📊 Disease severity assessment (Low, Medium, High)
* 💊 Treatment and prevention recommendations
* 🌱 Plant health insights
* 📄 Detailed analysis reports
* ⚡ FastAPI backend for scalable API services
* 🎨 Interactive Streamlit user interface

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **Backend:** FastAPI
* **AI Model:** Groq Llama Vision
* **Language:** Python
* **Image Processing:** Pillow, OpenCV
* **API Integration:** Groq API

## 📂 Project Structure

```text
leaf-disease-detection/
│
├── .streamlit/                 # Streamlit configuration
├── Leaf Disease/               # Leaf disease images/dataset
├── Media/                      # Screenshots, assets, demo files
│
├── .env                        # Environment variables
├── .env.example                # Sample environment variables
├── .gitignore                  # Git ignore rules
│
├── app.py                      # Streamlit frontend application
├── main.py                     # FastAPI backend and API routes
├── utils.py                    # Helper functions and image processing
├── test_api.py                 # API testing script
│
├── requirements.txt            # Project dependencies
├── vercel.json                 # Vercel deployment configuration
│
├── LICENSE                     # License information
└── README.md                   # Project documentation
```


## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/leaf-disease-detection.git
cd leaf-disease-detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key
```

### Run FastAPI Backend

```bash
uvicorn main:app --reload
```

### Run Streamlit Frontend

```bash
streamlit run app.py
```

## 🎯 How It Works

1. User uploads a leaf image.
2. Image is sent to the FastAPI backend.
3. Groq Llama Vision analyzes the image.
4. The system identifies potential diseases.
5. Severity level is determined.
6. Treatment and prevention recommendations are generated.
7. Results are displayed on the Streamlit dashboard.

## 📊 Output Example

* **Disease:** Early Blight
* **Severity:** Moderate
* **Confidence:** High
* **Treatment:**

  * Remove infected leaves
  * Apply recommended fungicide
  * Improve air circulation
  * Avoid overhead watering

## 🌟 Future Enhancements

* Multi-crop disease detection
* Real-time camera support
* Disease history tracking
* Weather-based disease prediction
* Mobile application integration
* PDF report generation

## 👨‍💻 Author

**Krishna Kumar**

B.Tech CSE | AI & Full-Stack Development Enthusiast

---

