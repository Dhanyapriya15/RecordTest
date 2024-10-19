# Audio Recording Application - RecordTest

This is a simple Java application that records audio from your microphone and saves it as a `.wav` file. It uses the `javax.sound.sampled` package to capture and save audio data.

## Features

- Records audio in `WAV` format.
- Prompts the user to start and stop recording with `JOptionPane` dialogs.
- Uses a separate thread for handling the audio recording process.

## Requirements

- JDK 8 or higher
- Microphone connected to your system
- The following Java libraries are required:
  - `javax.sound.sampled` (part of standard Java)
  - `javax.swing.JOptionPane` (for user prompts)

## How to Run

1. Clone this repository or download the source files.
2. Open the project in your IDE (such as Eclipse or IntelliJ IDEA).
3. Compile and run the `RecordTest.java` file.
4. Follow the prompts:
   - Press "OK" to start recording.
   - Press "OK" again to stop recording.
5. The recorded file (`record.wav`) will be saved in the project folder.

