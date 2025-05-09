# 🧠 ToxicCheck - Toxic Comment Classifier

ToxicCheck is a web-based tool for classifying and visualizing the toxicity of user-generated comments. It uses a trained deep learning model and a custom text vectorizer to detect toxic language and display severity using an interactive UI.

![ToxicCheck Screenshot](docs/demo_screenshot.png) <!-- Add your own screenshot if available -->

---

## 🚀 Features

- 🔍 **Real-Time Analysis** — Detect toxicity in seconds  
- 📊 **Toxicity Meter** — See severity from *Safe* to *Extreme*  
- 🧠 **Multi-Label Detection** — Identifies types like `toxic`, `insult`, `obscene`, etc.  
- 💡 **Dynamic UI** — Clean, responsive layout with animation and badges  
- 🔐 **Secure Backend** — Django-powered with CSRF protection

---

## 🛠️ Tech Stack

| Component     | Tech                       |
|---------------|----------------------------|
| Frontend      | HTML, CSS, JavaScript      |
| Backend       | Django, Django REST        |
| ML Model      | TensorFlow/Keras           |
| Vectorization | Custom `TfidfVectorizer`   |
| Format        | Model (`.h5`), Vectorizer (`.pkl`) |

---

