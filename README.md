# Major-Project_2023

# AI/ML Techniques in Emotion-Preserving Multilingual Video Translation for Practical Cross-Cultural Communication

This project demonstrates the implementation of AI/ML techniques for emotion-preserving multilingual video translation, facilitating cross-cultural communication. The code performs the following functions:

## Functionality Overview

### Step 1: Video and Audio Extraction

The initial step involves extracting the video and audio from the input video file using the FFmpeg library. The output includes separate video and audio files.

### Step 2: Background Noise Reduction

The code utilizes the `noisereduce` library to remove background noise from the extracted audio. The cleaned audio is saved as "vocals.wav."

### Step 3: Speech Transcription and Translation

The cleaned audio is transcribed using the Google Speech Recognition library. The transcribed text is then translated into the target language using the `translate` library. The translated text is saved to a file named "vocal_text.txt."

### Step 4: Text-to-Speech Synthesis

The code employs a multilingual text-to-speech (TTS) model to convert the translated text into speech. The TTS model used is "xtts_v2," and the generated speech is saved as "output.wav."

### Final Stretch: Video and Audio Merging

Finally, the script merges the original video with the synthesized multilingual audio to create the final output video file named "Final_output.mp4."

## How to Use

1. Ensure you have the required libraries installed by running the initial setup commands.
2. Input the path of the video file when prompted.
3. The script will execute the specified steps and provide the final multilingual video output.

Note: Adjustments to parameters may be needed based on specific requirements and characteristics of the input video and audio.

Feel free to explore and adapt the code for your use case!
