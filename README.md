# -GPT-Chatbot-with-Memory-LLM-LangChain-
: A GPT Chatbot with Memory using LangChain allows for more natural and context-aware conversations by retaining information across interactions. It leverages large language models and memory components to remember user inputs, preferences, or past topics for personalized responses.

# GPT Chatbot with Memory using LangChain

## Features
- Remembers previous messages using ConversationBufferMemory
- Easily extendable with tools, retrieval, agents, and more

## Setup Instructions
Firstly Unzip the file.

1. **Create virtual environment**:
```bash (Terminal)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

2. **Install dependencies**:
```bash  (Terminal)
pip install -r requirements.txt
```

3. **Set your own (Paid) OpenAI API key**:
Edit the `.env` file and add your OpenAI key:
```
OPENAI_API_KEY=your_openai_api_key_here
```

4. **Run the chatbot**:
```bash  (Terminal)
python main.py
```

Type `exit` to stop the chatbot.
