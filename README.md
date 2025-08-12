🥗 SAFE EAT

An AI-powered tool built with LLaMA 3.1 on Google Colab that analyzes food nutrition labels and ingredient lists to help fitness enthusiasts make informed eating choices.

---

 📌 Project Overview

Whether you're a fitness freak or just health-conscious, understanding what's really in your food can be tricky. This project allows you to upload a photo of a nutrition label and/or ingredients list (e.g., on a chocolate bar), and the AI will:

- 📊 Summarize key nutritional values (e.g. Rich in calcium)
- 🧾 Handle ingredient name variations (e.g. sugar disguised as caramel)
- ⚠️ Detect potentially harmful substances
- 🥛 Identify high sugar, caffeine, or other noteworthy contents
- 🌱 Check if the food is vegan-friendly
- ✅ Provide a clear, simple verdict on whether it’s safe to consume

Built for Google Colab, using LLaMA 3.1 as the core language model for text understanding and reasoning.

---

 🚀 Features

- Image-based analysis of nutrition labels & ingredient lists
- Edge case handling for disguised ingredients
- Nutrient quality scoring
- Simple, user-friendly summaries
- Vegan & allergy checks
- Runs fully in Google Colab — no setup hassle

---

 🛠 Tech Stack

- Python
- Google Colab
- LLaMA 3.1 (Meta AI)
- Transformers (Hugging Face)
- OpenCV / Tesseract OCR for text extraction
- Pandas for data handling

---

 📂 Project Structure

nutrition-ai/
│
├── notebooks/
│ └── Nutrition_AI_Analyzer.ipynb 
├── data/
│ └── sample_labels/
├── utils/
│ ├── ocr_utils.py 
│ ├── analysis_utils.py 
│ └── rules.py 
├── README.md
└── requirements.txt
