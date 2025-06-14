🖼️ Multi-User AI Image Generator
This project allows multiple users to collaboratively generate a creative image using the Gemini Flash LLM (via LangChain) and Stability AI’s image generation API. 
Each user contributes a word or phrase, and the model combines them into a concise, optimized prompt that is used to generate an AI image.

🚀 Features
🤖 Uses Google Gemini 2.0 Flash (via langchain-google-genai) to generate a meaningful prompt.

🖼️ Calls the Stability AI image generation API to create an image based on that prompt.

👥 Takes input from multiple users.

📦 Built with an interactive Gradio UI.

📄 Displays both the generated prompt and the image in real time.

🧠 How It Works
The user enters the number of participants.

A set of textboxes appear (one for each user).

Each participant enters a word or phrase.

The app:

Combines them into a single prompt via Gemini Flash LLM.

Sends this prompt to Stability AI to generate an image.

The final prompt and image are shown.

🛠️ Requirements
Python 3.8+

Dependencies listed below

🔗 APIs Used
Gemini API (via LangChain)

Stability AI Image Generation API
