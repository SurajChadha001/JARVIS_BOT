

````markdown
# Jarvis Voice Assistant

**Jarvis** is a voice-activated desktop assistant built with Python.  
It can search Wikipedia, open websites, play music, tell the current time, and more—all with voice commands.

## Features

- Voice recognition using Google Speech Recognition
- Text-to-speech responses
- Search Wikipedia and read summaries aloud
- Open YouTube, Google, or StackOverflow
- Play music from a local directory
- Tell the current time

## Requirements

- Python 3.6+
- `pyttsx3`
- `SpeechRecognition`
- `wikipedia`
- `pyaudio`
- (Optional) `pipwin` (to install PyAudio on Windows)

## Installation

1. **Clone the repository** (or copy the files to a folder):

   ```bash
   git clone https://github.com/yourusername/jarvis-voice-assistant.git
   cd jarvis-voice-assistant
````

2. **Create a virtual environment** (recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate    # On Linux/Mac
   venv\Scripts\activate       # On Windows
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

   > **Note:**
   > If you get errors with `PyAudio` on Windows, run:
   >
   > ```bash
   > pip install pipwin
   > pipwin install pyaudio
   > ```

4. **Update the music folder path:**

   * In the code, change `music_dir = 'E:\\music'` to your actual music folder path.

## Usage

1. **Run the assistant:**

   ```bash
   python jarvis.py
   ```

2. **Speak your command when prompted.**

   Example commands:

   * “Wikipedia Albert Einstein”
   * “Open YouTube”
   * “Play music”
   * “What is the time?”



## Troubleshooting

* If the microphone is not working, check your system permissions.
* If voice recognition is inaccurate, try speaking clearly and slowly.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

**Made with ❤️ using Python**


