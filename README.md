 🤖 JARVIS - Your Personal Desktop Voice Assistant

JARVIS is an AI-powered desktop voice assistant built using Python. It can perform various tasks such as web searching, opening applications, sending emails, playing music, reporting the weather, and more — just like Iron Man’s J.A.R.V.I.S.

---

 🧠 Features

- 🎙 Voice command recognition using `speech_recognition`
- 💬 Text-to-speech using `pyttsx3`
- 🌐 Search the web, Wikipedia, or YouTube
- 📂 Open applications like Chrome, Notepad, etc.
- 📧 Send emails via voice
- 🎵 Play music from your PC
- 📅 Tell time, date, and day
- 🌦 Get live weather reports
- 🧮 Perform simple calculations
- 💻 Fully offline capability for basic commands

---

## 🛠️ Technologies Used

- Python 3
- `speech_recognition`
- `pyttsx3`
- `wikipedia`
- `smtplib`
- `os`, `webbrowser`, `datetime`, etc.

---

## 📁 Folder Structure

```

JARVIS/
├── main.py               # Main script to run JARVIS
├── features/             # Folder for feature modules
├── utils/                # Utility functions
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

````

---

## ⚙️ Installation Steps

### 1. Clone the Repository

```bash
git clone https://github.com/SoubhagyaGhoshal/JARVIS.git
cd JARVIS
````

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
```

### 3. Install Required Packages

bash
pip install -r requirements.txt


If `pyaudio` fails to install, download the `.whl` from [Gohlke's site](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio), then install manually:

```bash
pip install PyAudio‑0.2.11‑cp39‑cp39‑win_amd64.whl
```

---

## 🚀 How to Run

```bash
python main.py
```

Once started, JARVIS will greet you and wait for your voice commands.

---

## 🎤 Example Commands

* "Open YouTube"
* "What is the weather in Delhi?"
* "Play music"
* "Tell me a joke"
* "Send email"
* "Search Wikipedia for Python"
* "Shutdown the system"

---

## ❗Troubleshooting

* **PyAudio Error:** Install manually using `.whl` file.
* **Microphone not detected:** Ensure microphone permissions are enabled and check audio drivers.
* **App not launching:** Check `main.py` for syntax errors and missing libraries.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Soubhagya Ghoshal**
[GitHub](https://github.com/SoubhagyaGhoshal) | [LinkedIn](https://www.linkedin.com/in/soubhagyaghoshal/) 

---

## ⭐ Star the Repo

If you like this project, don't forget to ⭐ the repository!


