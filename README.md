🌐 Multimodal Sentiment & Emotional Impact Analyzer
A multimodal AI Chrome Extension that analyzes the emotional tone and sentiment of any webpage using text + image fusion via pretrained models (BERT + ResNet50). The backend runs locally on Flask and serves results instantly to your Chrome Extension.
------------------------------------------------------------
🚀 Features
✅ Extracts text and primary image from any webpage
✅ Performs sentiment analysis (Positive / Negative / Neutral)
✅ Detects emotional intensity (Low / Medium / High)
✅ Extracts top keywords using TF-IDF
✅ Fuses text (BERT) and image (ResNet50) features for multimodal representation
✅ Simple Chrome popup interface to analyze any open tab instantly
------------------------------------------------------------
🧠 Tech Stack
Frontend: Chrome Extension (HTML, JS, CSS)
Backend API: Flask (Python)
Text Model: BERT (bert-base-uncased)
Sentiment Model: DistilBERT (distilbert-base-uncased-finetuned-sst-2-english)
Image Model: ResNet50 (TensorFlow / Keras)
Keyword Extraction: TF-IDF (scikit-learn)
------------------------------------------------------------
⚙️ Installation
1. Clone or Download:
   git clone https://github.com/yourusername/multimodal-analyzer.git
   cd multimodal-analyzer
2. Setup Environment:
   python -m venv venv
   .\venv\Scripts\activate
3. Install Dependencies:
   pip install flask torch torchvision torchaudio tensorflow transformers pillow scikit-learn cloudscraper beautifulsoup4
4. Run the Flask API:
   python api_server.py
------------------------------------------------------------
🧩 Chrome Extension Setup
1. Go to chrome://extensions
2. Enable Developer Mode
3. Load Unpacked → select multimodal_extension/
4. Open popup → click “Analyze Current Page”
------------------------------------------------------------
🧩 Example Output
URL: https://www.accuweather.com/en/in/chennai/206671/weather-forecast/206671
Emotional Impact: No
Sentiment Type: NEUTRAL
Emotion Intensity: Low
Top Keywords: ['partly', 'cloudy', 'showers', 'morning', 'hours']
Fused Vector Shape: (2816,)
------------------------------------------------------------
🧠 Models Used
BERT - for text embedding
DistilBERT - for sentiment detection
ResNet50 - for image embedding
TF-IDF - for keyword extraction
------------------------------------------------------------
🛠 Libraries Used
flask, torch, torchvision, torchaudio, tensorflow,
transformers, pillow, scikit-learn, cloudscraper,
beautifulsoup4, requests, numpy
------------------------------------------------------------
👨‍💻 Author
Balanagu Krishna Kiriti
Kethamreddy Vishnu Vardhan Reddy
Koteru Tarun
Pratyush Kumar V
Shakti Narayan

