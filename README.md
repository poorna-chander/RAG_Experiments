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

####

how the example was embedding the image:

https://github.com/langchain-ai/langchain/blob/master/libs/community/langchain_community/vectorstores/chroma.py#L20

https://github.com/langchain-ai/langchain/blob/master/libs/experimental/langchain_experimental/open_clip/open_clip.py
