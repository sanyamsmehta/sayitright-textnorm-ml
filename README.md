**sayitright-textnorm-ml** is a machine learning-powered text normalization engine designed to transform raw written expressions into fluent, human-readable spoken forms. Built for downstream applications in Text-to-Speech (TTS), Automatic Speech Recognition (ASR), and other NLP tasks, LangMorph tackles the complexities of converting tokens like 12:47 to "twelve forty-seven" or $3.16 to "three dollars, sixteen cents" with high accuracy and linguistic finesse. 

**What it Does:** 
- Learns language patterns from millions of token-level transformations
- Predicts normalized spoken equivalents using ML models like:
- FastText
- T5 Transformer
- CRF
- AdaBoost, kNN, and more
- Handles challenging cases like:
- Dates (11/17/09 → "november seventeenth oh nine")
- Currency ($18,887 → "eighteen thousand eight hundred eighty seven dollars")
- Time (3:00 PM → "three p m")
- URLs, addresses, and fractions 

**Key Features:**
- Clean dataset of over 9 million tokens across 16 linguistic classes
- Multiple models evaluated on performance, speed, and interpretability
- Comparative results using accuracy and F1 scores
- Modular Jupyter notebooks for exploration and experimentation 

**Tech Stack:**
- Python, Pandas, Scikit-learn
- FastText (Facebook)
- T5 (Google Transformers via HuggingFace)
-CRF++ / sklearn-crfsuite
- Jupyter Notebooks

**Use Cases:** 
- Voice Assistants
- TTS/ASR Engines
- Digital Accessibility Tools
- Conversational AI Preprocessing
- Language Standardization

To read more, refer - [Report](https://docs.google.com/document/d/1E6cTCHRMHmiN7xopgDCIRmK2yb4w0o7D/edit?usp=sharing&ouid=112722355947732076323&rtpof=true&sd=true)
