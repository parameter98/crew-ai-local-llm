# CrewAI Local LLM

Run CrewAI locally for free!

# Steps

- Install Ollma
- Create custom local LLM made for CrewAI
  - Run the ./scripts/create_model.sh script
    - Make this script executable by running `chmod +x ./scripts/create_model.sh`
      or copy and paste commands into terminal
  - This will create a model file in the models directory
  - To change models, edit the create_model.sh script
- Verify you are using local llm
  - `cat ~/.ollama/logs/server.log`

# Tips

- If using multiple models,

# Warnings & Recommendations

- Ollama doesn't work with Async tasks and a bunch of newer CrewAI features yet.
- Lose context. Be very explicit in tasks. Not generic.

# Resources

- Want to find out which LLMs support which features in CrewAI? Here's the link for you:
  - https://python.langchain.com/docs/integrations/llms/
- Learn more about Modelfiles:
  - https://github.com/ollama/ollama/blob/main/docs/modelfile.md
- Check out CrewAI's instructions for working with Ollama and running LLMs locally:
  - https://docs.crewai.com/how-to/LLM-Connections/#connect-crewai-to-llms

## 현재 [serp](https://google.serper.dev/news) 링크로 가보면 unauthrized 됨, 무료 계정을 만들고 유효한 api 키로 변경할 필요가 있음. https://sec-api.io/ 의 API 또한 마찬가지로 API 키 변경할 것.
