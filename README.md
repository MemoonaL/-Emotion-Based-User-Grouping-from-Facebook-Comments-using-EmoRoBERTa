# 💬 Emotion-Based User Grouping from Facebook Comments using EmoRoBERTa

This project uses **[EmoRoBERTa](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base)** — a RoBERTa model fine-tuned on the GoEmotions dataset — to detect emotions in Facebook user comments and group them accordingly.

---

## 📌 Features

- ✅ Emotion classification on Facebook posts using transformer models
- 📊 Visualizations of dominant emotional trends (Bar and Pie charts)
- 📁 Export results to CSV and Excel
- 🚀 Easy to run using Jupyter Notebook or Python script

---

## 📂 Dataset

The dataset includes Facebook comments in the following format:

| Column   | Description                    |
|----------|--------------------------------|
| `FBPost` | Facebook post or comment text  |

---

## 🤖 Model: EmoRoBERTa

- Model used: [`j-hartmann/emotion-english-distilroberta-base`](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base)
- Detects the following emotions:
  - `joy`, `sadness`, `anger`, `fear`, `surprise`, `disgust`, `neutral`
- Built using HuggingFace's 🤗 `transformers` library

---

# 💡 Use Cases
Understanding audience mood shifts

Grouping users for targeted marketing

Detecting emotional trends on social platforms

# 🧠 Future Enhancements
Interactive dashboard using Plotly or Streamlit

Time-based emotion tracking

Grouping by user (if user IDs are available)

# 🙌 Credits
Model by: Jan Hartmann

Built using: HuggingFace Transformers
