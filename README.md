An AI-powered mental health chatbot that listens, understands, and responds like a caring best friend. It supports both voice and text input, and can respond with comforting audio messages.

💡 Features
🎤 Voice Input – Speak directly using your microphone

✏️ Text Input – Type out how you're feeling

💬 Emotion-aware Chatbot – Responds with empathy using Groq's LLaMA3 model

🔊 Voice Output – Replies with speech using Google Text-to-Speech (gTTS)

🖥️ Clean UI – Built with Gradio for ease of use

🚀 Getting Started (Google Colab)
Install dependencies by running:

!pip install groq gradio gtts speechrecognition pydub
client = groq.Groq(api_key="your_groq_api_key_here") 
for now api key is already updated

Run all cells and launch the interface.

🛠️ Tech Stack
Groq API – For fast, intelligent responses using LLaMA3

Gradio – For building the interactive web UI

gTTS – For generating voice replies

SpeechRecognition + pydub – For converting audio to text

📌 Notes
Use Chrome for best voice input compatibility in Google Colab

Ensure microphone permissions are enabled

Voice output is optional and can be toggled on/off

