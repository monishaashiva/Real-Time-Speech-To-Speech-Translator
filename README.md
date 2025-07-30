
# 🌐 Real-Time-Speech-To-Speech-Translator

**Speak once. Understand anywhere.**  
A real-time speech-to-speech translator that listens to your voice, translates it into a target language, and plays the translated speech — all using Python.

## 🎯 Features

- 🎤 **Speech Recognition** – Converts your voice to text  
- 🌍 **Translation** – Translates the recognized text into the target language  
- 🔊 **Text-to-Speech** – Converts translated text into spoken output  
- 🎧 **Audio Output** – Saves and plays the translated speech as an MP3 file (`hello.mp3`)

## 📁 Project Structure

```

Real-Time-Speech-To-Speech-Translator/


├── app.py         
├── hello.mp3      
└── README.md      

````

## ⚙️ Requirements

Make sure Python 3 is installed. Then install the required libraries:

```bash
pip install SpeechRecognition googletrans==4.0.0-rc1 gtts playsound
````

## 🚀 How to Run the Project

1. Connect your microphone and speakers.
2. Open a terminal/command prompt inside the project folder.
3. Run the program:

```bash
python app.py
```

4. Speak when prompted.
5. The app will:

   * Recognize your speech
   * Translate it to the target language
   * Convert it to speech
   * Save it as `hello.mp3` and play the audio

## 💡 Technologies Used

* **Python 3**
* [`SpeechRecognition`](https://pypi.org/project/SpeechRecognition/)
* [`googletrans`](https://pypi.org/project/googletrans/) – unofficial Google Translate API
* [`gTTS`](https://pypi.org/project/gTTS/) – Google Text-to-Speech
* [`playsound`](https://pypi.org/project/playsound/) – to play audio in Python

## 📌 Notes

* You must be **connected to the internet** while running the program.
* You can **change the source and destination languages** in `app.py`.
* `hello.mp3` will be overwritten each time you run the app.

## 🚀 Future Enhancements

* [ ] Add graphical interface (GUI) for selecting languages
* [ ] Allow continuous live translation
* [ ] Support more language output options
* [ ] Add language detection and error handling

## 🧑‍💻 Author

**S Monishaa**
GitHub: [@monishaashiva](https://github.com/monishaashiva)

## 📄 License

This project is licensed under the **MIT License**.
You are free to use, modify, and share it with attribution.
