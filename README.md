
# Speech Recognition and Transcription 

This is a Python-based desktop application that allows users to transcribe audio using Google's Speech Recognition API. Users can upload audio files to convert into text or can record the entered text in available voice.
---
### Features

Upload Audio File: Transcribe speech from uploaded audio files in formats like .wav, .mp3, and .flac.

Record Audio: Record audio in real time using a microphone and transcribe it instantly.

Simple GUI: User-friendly interface created with Tkinter.

Text Output: View the transcription in a text box within the app.



---

### Requirements

Dependencies

Make sure you have the following Python libraries installed:

tkinter (comes pre-installed with Python)

speechrecognition

pyaudio (required for microphone input)


### Installation

1. Clone the repository:

git clone https://github.com/yourusername/speech-recognition-app.git


2. Navigate to the project directory:

cd speech-recognition-app


3. Install the required dependencies:

pip install SpeechRecognition pyaudio


---

### Usage

1. Run the application:

python app.py


2. Use the GUI to:

Upload Audio File: Click the "Upload Audio File" button to select an audio file for transcription.

Record Audio: Click the "Record Audio" button to record your voice and transcribe it.


3. The transcription will appear in the text box.


---

### Project Structure

app.py: The main application script containing the GUI and transcription logic.
In the beggining required Python Modules are imported which are further used to build the code.

---

### Notes

Ensure your microphone is enabled and working for the Record Audio feature.

For accurate results, use clear and noise-free audio files.

Internet connection is required for the transcription as it uses Google's Speech Recognition API.


---

### Troubleshooting

Microphone not working: Ensure pyaudio is correctly installed. On some systems, you might need to install additional dependencies (e.g., portaudio for Linux).

Speech not recognized: Check the audio quality or try speaking clearly in a quiet environment.



---

