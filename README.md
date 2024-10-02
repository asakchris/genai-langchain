### Ollama setup
1. Go to https://ollama.com/download, download Ollama and install it
2. Open a Terminal and run `ollama` to ensure it’s installed successfully 
3. Ollama is a software that allows us to download and run open source LLMs
4. Check this link for Ollama supported models - https://github.com/ollama/ollama
5. Run `ollama pull gemma:2b` to download the model
6. To test the model, run `ollama run gemma:2b`, it opens a prompt, where we can enter the prompts
7. To quit the model, run `/bye`


streamlit run ./02-LangChain-OpenAI-Ollama/app.py