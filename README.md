EmoChatBot

A simple chatbot built using GPT-2 and trained on an emotional dialogue dataset.
The model is capable of generating human-like conversational responses and attempts to capture emotions from dialogues.

🚀 Features

Trained on an emotional conversations dataset.

Uses GPT-2 architecture with fine-tuning.

Supports interactive chatting in the notebook.

Basic conversation flow with improved coherence using training data.

📂 Project Structure
├── dataset/                # Dataset files (CSV with dialogues)  
├── training/               # Training scripts  
├── models/                 # Saved fine-tuned model  
├── chatbot_interactive.py  # Chatbot interactive script  
├── requirements.txt        # Dependencies  
└── README.md               # Project description  

⚙️ Installation

Clone the repository:

git clone https://github.com/your-username/EmoChatBot.git
cd EmoChatBot


Install dependencies:

pip install -r requirements.txt


Run the chatbot:

python chatbot_interactive.py

📊 Training

The chatbot was fine-tuned using PyTorch and Hugging Face Transformers.
Steps followed:

Preprocessed conversations into tokenized format.

Created train, validation, and test splits.

Fine-tuned GPT-2 for 2 epochs.

Saved trained model for chatbot inference.

💬 Example Usage
You: Hello  
Chatbot: Hi, how are you?  

You: I’m feeling sad today.  
Chatbot: I’m sorry to hear that. I hope things get better soon.  

🔮 Future Improvements

Train on a larger and more diverse dataset.

Add emotion classification layer for better emotional understanding.

Deploy as a web app with Flask or Streamlit.
