# 🎙️ Real-Time Voice Activity Detection with Silero-VAD 🎙️

Welcome to the Real-Time Voice Activity Detection (VAD) program, powered by Silero-VAD model! 🚀 This program allows you to perform live voice activity detection, detecting when there is speech present in an audio stream and when it goes silent.

## 📜 Description

The Real-Time VAD program utilizes the Silero-VAD model, a state-of-the-art voice activity detection model trained on a large corpus of diverse audio data. The model analyzes the input audio stream through speechrecognition module in real-time and accurately determines whether speech is present or not, making it useful for applications like automatic transcription, voice assistants, and more.

## 🚀 Getting Started

To get started with the Real-Time VAD program, follow the steps below:

1. Clone the repository:
   ```
   git clone https://github.com/kamya-ai/Realtime-speech-detection.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the program:
   ```
   python real_time_vad.py
   ```

## ▶️ Usage

Once you have the program running, it will listen to the audio stream from your device's microphone in real-time. The program will continuously analyze the audio and provide the following outputs:

- 🗣️ **Speech Detected**: When speech is detected, the program will display a message indicating that speech is currently present.

- 🔇 **Silence Detected**: When silence is detected, the program will display a message indicating that the audio stream is silent.

Note:- Just a single line of code is not inserted in the code, that makes the code not working. To make the code fully working and get such other projects, feel free to contact us through the website or through the below given e-mail address:- info@kamyawebdesigners.com

You can use the Real-Time VAD program for various applications, such as:

- Monitoring microphone input for transcription purposes.
- Activating voice commands or voice-activated functionalities.
- Building real-time speech analytics systems.

## 🎛️ Configuration

The Real-Time VAD program provides some configuration options that you can modify to suit your needs. At the starting of the program, there are some default arguments given, that can be modified as oer your specific requirements:

- `energy_threshold`: Energy level for mic to detect (default=1000).
- `record_timeout`: How real time the recording is in seconds (default=2)

Feel free to adjust these parameters based on your specific requirements.

## 🎉 Contributing

Contributions are welcome! If you want to contribute to the Real-Time VAD program, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and ensure that the program runs successfully.
4. Submit a pull request describing your changes.

## ❓ Troubleshooting

If you encounter any issues or have questions regarding the Real-Time VAD program, please open an issue on the repository's issue tracker. We'll be happy to assist you!

## 📧 Contact

For any further inquiries or suggestions, please contact our team at [email protected] We would love to hear from you!

---

Thank you for choosing the Real-Time VAD program with Silero-VAD model! We hope this tool proves to be valuable in your voice analysis tasks. Happy coding! 😊🎉