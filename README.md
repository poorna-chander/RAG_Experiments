# RAG_Experiments

pip install langchain
pip install openai
export OPENAI_API_KEY="..."

langchain expression labguage (LCEL) -- FOR CHAINING COMPONENTS

core components:

1. LLM (single hit) / ChatModel (with history)
2. Prompt template
3. Output Parser

message: (content, role)

roles:

HumanMessage
AIMessage
SystemMessage
FunctionMessage
