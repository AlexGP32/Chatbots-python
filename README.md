# Chatbots-python

Un program care integreaza doua abordari de chatbot: unul rule-based cu **RiveScript** si unul bazat pe un **LLM local** rulat prin Ollama.

# Cerinte

- Python 3.10+
- pip install rivescript ollama
- Pentru chatbot(LLM).py: [Ollama](https://ollama.com/) instalat local, cu modelul gemma2:2b descarcat (ollama pull gemma2:2b) si serviciul Ollama pornit

# Rulare

Chatbot rule-based (RiveScript):
python "chatbot(Rule).py"

Foloseste regulile din Brain-rive.txt. Se inchide cu /quit.

Chatbot cu LLM (Ollama):
python "chatbot(LLM).py"
UniBot, un asistent universitar care raspunde pe baza unui set de reguli de prioritate definite in prompt. Se inchide scriind exit.
