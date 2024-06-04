# DSP_project_Voice_Frequency_Encoder_Decoder
This DSP application encodes text into audio signals using specific frequencies and decodes audio back to text. Features include recording audio, saving and playing encoded signals, and decoding audio files. The GUI simplifies usage, making it accessible for encoding and decoding tasks.
# Voice-Frequency Encoder and Decoder

This project encodes text into audio signals and decodes audio back to text using specific frequency patterns. Features include recording, saving, playing encoded signals, and decoding audio files via a user-friendly GUI.

## Features

- Encode text to audio signals.
- Record and encode spoken words.
- Save and play generated signals.
- Decode audio files back to text.
- User-friendly GUI.

## Installation

### Prerequisites

- Python 3.x
- Required Python packages:

    ```bash
    pip install pyaudio wave SpeechRecognition numpy tkinter sounddevice scipy matplotlib pyttsx3
    ```

### Running the Application

1. Clone the repository:

    ```bash
    git clone https://github.com/Imran-Khan118/DSP_project_Voice_Frequency_Encoder_Decoder.git
    cd DSP_project_Voice_Frequency_Encoder_Decoder
    ```


## Usage

### Encoding and Saving

1. Enter the text you want to encode in the text entry field.
2. Click on "Save the generated signal as (.wav)" to save the encoded signal as a WAV file.
3. You can also play the generated signal by clicking on "Play the generated signal".

### Recording and Encoding

1. Click on "Record Audio and Encode" to start recording your voice.
2. The application will convert your recorded speech to text and then encode it into a signal.

### Decoding

1. Click on "Upload Audio File (.wav)" to upload a WAV file for decoding.
2. Click on "Run Decoder" to choose between decoding using frequency analysis or filters.
3. The decoded text will be displayed in the result text area.
4. You can play the decoded text using text-to-speech by clicking on "Play Decoded Text".

## Contributors

- Faizer
- Imran
- Rifat

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
