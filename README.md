Chatbot with Gradio and Hugging Face Transformers
This repository contains code for building a chatbot using the Hugging Face Transformers library and Gradio for both text and speech input. Two versions of the chatbot are included:

Text-based Chatbot (CHAT BOT V1):

Uses the Hugging Face pipeline for question-answering.
Gradio is used to create a simple user interface where users can input context and questions to get answers.
Speech-based Chatbot (CHAT BOT V2):

Incorporates speech recognition using the SpeechRecognition library along with the text-based chatbot.
Gradio is used to create an interface where users can speak their questions via a microphone, and the chatbot responds with answers.
Dependencies
Make sure to install the required dependencies before running the code:

bash
Copy code
pip install transformers gradio SpeechRecognition
Usage
Text-based Chatbot (CHAT BOT V1):
Run the notebook text_chatbot.ipynb.
Follow the instructions in the notebook to input context and questions using the Gradio interface.
Speech-based Chatbot (CHAT BOT V2):
Run the notebook speech_chatbot.ipynb.
Follow the instructions in the notebook to speak questions via a microphone using the Gradio interface.
Note
The chatbot models are based on the deepset/roberta-base-squad2 model. You can change the model by updating the model variable in the code.

Gradio may issue a warning about the theme not being available. This can be ignored as it does not affect the functionality of the chatbot.

Additional Information
For more information on Gradio and Hugging Face Transformers, please refer to their documentation:

Gradio: https://www.gradio.app/
Hugging Face Transformers: https://huggingface.co/transformers/
