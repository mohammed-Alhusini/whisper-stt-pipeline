# Audio Transcription Chatbot

This project focuses on developing an advanced audio transcription and summarization system using Python and various audio processing libraries. The main goal is to automate the process of transcribing audio files into text and then summarizing the key points from the transcriptions. The project involves several key components:

## Audio Handling and Processing:

The system utilizes the pydub library for handling and processing audio files. It includes functionalities for loading audio files, determining their length, and splitting them into smaller, manageable chunks if they exceed a specified duration.

## Transcription:

Leveraging the capabilities of the OpenAI API, the system transcribes audio chunks into text. This allows for handling long audio files by processing them in segments, ensuring efficient and accurate transcriptions.

## Summarization:

The transcribed text is then processed to extract key points. Using advanced natural language processing techniques, the system generates concise summaries, highlighting the most important information from the audio content.

## User Interface:

The project includes a user-friendly interface built with gradio, enabling users to interact with the system easily. Users can upload audio files, receive transcriptions, and view summaries directly through the interface.

