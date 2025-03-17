# Live Speech Translation

## 📌 Overview
This project is a **real-time speech translation system** that converts spoken language into text, translates it into another language, and outputs the translated text as speech. It leverages **Natural Language Processing (NLP)** techniques and text-to-speech (TTS) technologies to provide seamless multilingual communication.

## 📂 Project Structure
```
├── dataset/                # (Optional) Any pre-recorded speech samples
├── notebooks/              # Jupyter notebooks for implementation
├── scripts/                # Python scripts for speech recognition & translation
├── requirements.txt        # Dependencies
├── Translator_Prototype.ipynb  # Main Jupyter notebook
└── README.md               # Project documentation
```

## ⚙️ Features
- **Real-Time Speech Recognition:** Converts live speech into text using **SpeechRecognition**.
- **Multilingual Translation:** Uses **DeepTranslator** to translate text between multiple languages.
- **Text-to-Speech (TTS):** Converts translated text into speech using **gTTS (Google Text-to-Speech)**.
- **User-Friendly Execution:** Simple execution flow for quick translation.

## 🚀 Installation & Usage
### Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install -r requirements.txt
```

### Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/live-speech-translation.git
   cd live-speech-translation
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Translator_Prototype.ipynb
   ```
3. Follow the steps in the notebook to test the speech-to-text and translation features.

## 📊 Supported Languages
- **Speech-to-Text:** Supports multiple languages using **Google Web Speech API**.
- **Translation:** Supports translation for **over 100 languages**.
- **Text-to-Speech:** Outputs translated speech in supported languages.

## 🛠 Technologies Used
- Python
- SpeechRecognition
- DeepTranslator
- gTTS (Google Text-to-Speech)
- Playsound (for audio output)

## 📌 Future Improvements
- Implement a **GUI** for a user-friendly experience.
- Enhance translation accuracy with **Transformer-based NLP models**.
- Support **offline speech recognition** for better accessibility.
- Deploy as a **mobile app** for real-world usage.

## 🤝 Contributing
Feel free to fork this repo, open issues, or submit pull requests. Contributions are always welcome! 🚀

## 📜 License
This project is licensed under the MIT License.

---
🔗 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/yxsh-agarwal/) | [GitHub](https://github.com/yxsh-uwu)

