# CodeAlpha — Artificial Intelligence Internship

Three applied AI projects built during the **CodeAlpha Virtual AI Internship** (June – July 2026).
Each project was independently developed, submitted, and accepted, covering NLP, API integration,
and real-time computer vision. The internship concluded with an official **Completion Certificate**
and **Letter of Recommendation**.

---

## 🏅 Internship Details

| Field | Details |
|---|---|
| **Organization** | CodeAlpha |
| **Domain** | Artificial Intelligence |
| **Mode** | Virtual · Remote |
| **Duration** | 10th June 2026 – 10th July 2026 |
| **Certificate ID** | CA/DF1/134778 |
| **Submitted by** | Kshitij Mittal · IILM University, Greater Noida |

---

## 📁 Projects

### 1. 🤖 FAQ Chatbot
**Path:** [`chatbot_for_FAQs/`](https://github.com/AkarshKumar1/CodeAlpha_FAQChatbot)

A retrieval-based FAQ assistant that uses **TF-IDF vectorization** and **cosine similarity** to
semantically match user queries against a curated question-answer knowledge base, served through
an interactive **Streamlit** web interface.

**How it works:**
- FAQ corpus is preprocessed with NLTK (tokenization, lemmatization, stopword removal)
- Queries and corpus are vectorized using `TfidfVectorizer` from scikit-learn
- Cosine similarity identifies the closest match; fallback response returned if below threshold

**Tech Stack:**

| Library | Role |
|---|---|
| `nltk` | NLP preprocessing pipeline |
| `scikit-learn` | TF-IDF vectorization + cosine similarity |
| `streamlit` | Web UI |
| `Python 3.x` | Core language |

**Run:**
```bash
cd chatbot_for_FAQs
pip install -r requirements.txt
streamlit run chatbot.py
```

---

### 2. 🌐 Language Translation Tool
**Path:** [`language_translation_tool/`](https://github.com/AkarshKumar1/CodeAlpha_LanguageTranslationTool)

A multilingual translation web app integrating the **Google Translate API** via the
`deep-translator` library. Users select source and target languages from dropdowns and receive
real-time translations through a clean **Streamlit** interface.

**How it works:**
- `GoogleTranslator` from `deep-translator` abstracts the API calls
- Streamlit widgets handle language selection and text input
- Translation is triggered on submit; output rendered instantly in the UI

**Tech Stack:**

| Library | Role |
|---|---|
| `deep-translator` | Google Translate API wrapper |
| `streamlit` | Web UI |
| `Python 3.x` | Core language |

**Run:**
```bash
cd language_translation_tool
pip install -r requirements.txt
streamlit run translator.py
```

---

### 3. 👁️ Object Detection & Tracking
**Path:** [`object_detection_and_tracking/`](https://github.com/AkarshKumar1/CodeAlpha_ObjectDetectionTracking)

A real-time computer vision pipeline that detects and tracks multiple objects from a **live webcam
feed** using **YOLOv8** (Ultralytics) and **OpenCV**. Bounding boxes, class labels, and confidence
scores are overlaid on each frame, with object identities persisted across frames via YOLOv8's
built-in tracker.

**How it works:**
- `cv2.VideoCapture` streams live webcam frames
- `model.track()` runs per-frame detection + ByteTrack-based multi-object tracking
- OpenCV renders annotated frames in a real-time display window

**Tech Stack:**

| Library | Role |
|---|---|
| `ultralytics` | YOLOv8 detection + tracking |
| `opencv-python` | Frame capture, annotation, display |
| `numpy` | Array operations |
| `Python 3.x` | Core language |

**Run:**
```bash
cd object_detection_and_tracking
pip install -r requirements.txt
python detection.py
```
> Requires a connected webcam. Press `q` to quit.

---

## 📜 Internship Completion Certificate

<p align="center">
  <img src="certificate/Certificate_Akarsh_Kumar.jpg"
       alt="CodeAlpha Artificial Intelligence Internship Completion Certificate"
       width="900">
</p>

**Issued:** 11th July 2026  . **Student ID:** CA/DF1/134778

---

## 👤 Author

**Akarsh Kumar**
B.Tech CSE (AI/ML) · IILM University, Greater Noida
