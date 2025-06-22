# End-to-End-Nutritionist-Generative-AI-Doctor-Using-Google-Gemini-Pro-Vision

# 🏥 Health Management App - Streamlit + Gemini Vision Integration

This application uses Google's **Gemini 1.5 Flash Vision API** and **Streamlit** to analyze food images and generate nutritional data, including estimated calorie counts for each item.

---

## 📦 Dependencies

- `streamlit` – For building the web app UI
- `PIL (Pillow)` – To handle image display
- `dotenv` – To securely load API keys from environment
- `google.generativeai` – To access Gemini API services

---

## 📁 File Structure & Key Sections

### 1. **Environment Setup**

```python
from dotenv import load_dotenv
load_dotenv()

