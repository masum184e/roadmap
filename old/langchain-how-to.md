## Installation
1. How to: install LangChain packages  
2. How to: use LangChain with different Pydantic versions

## Key features
1. How to: return structured data from a model  
2. How to: use a model to call tools  
3. How to: stream runnables  
4. How to: debug your LLM apps

## Components

### Chat models
1. How to: do function/tool calling  
2. How to: get models to return structured output  
3. How to: cache model responses  
4. How to: get log probabilities  
5. How to: create a custom chat model class  
6. How to: stream a response back  
7. How to: track token usage  
8. How to: track response metadata across providers  
9. How to: use chat model to call tools  
10. How to: stream tool calls  
11. How to: handle rate limits  
12. How to: few shot prompt tool behavior  
13. How to: bind model-specific formatted tools  
14. How to: force a specific tool call  
15. How to: work with local models  
16. How to: init any model in one line  
17. How to: pass multimodal data directly to models

### Messages
1. How to: trim messages  
2. How to: filter messages  
3. How to: merge consecutive messages of the same type

### Prompt templates
1. How to: use few shot examples  
2. How to: use few shot examples in chat models  
3. How to: partially format prompt templates  
4. How to: compose prompts together  
5. How to: use multimodal prompts

### Example selectors
1. How to: use example selectors  
2. How to: select examples by length  
3. How to: select examples by semantic similarity  
4. How to: select examples by semantic ngram overlap  
5. How to: select examples by maximal marginal relevance  
6. How to: select examples from LangSmith few-shot datasets

### LLMs
1. How to: cache model responses  
2. How to: create a custom LLM class  
3. How to: stream a response back  
4. How to: track token usage  
5. How to: work with local models

### Output parsers
1. How to: parse text from message objects  
2. How to: use output parsers to parse an LLM response into structured format  
3. How to: parse JSON output  
4. How to: parse XML output  
5. How to: parse YAML output  
6. How to: retry when output parsing errors occur  
7. How to: try to fix errors in output parsing  
8. How to: write a custom output parser class

### Document loaders
1. How to: load PDF files  
2. How to: load web pages  
3. How to: load CSV data  
4. How to: load data from a directory  
5. How to: load HTML data  
6. How to: load JSON data  
7. How to: load Markdown data  
8. How to: load Microsoft Office data  
9. How to: write a custom document loader

### Text splitters
1. How to: recursively split text  
2. How to: split HTML  
3. How to: split by character  
4. How to: split code  
5. How to: split Markdown by headers  
6. How to: recursively split JSON  
7. How to: split text into semantic chunks  
8. How to: split by tokens

### Embedding models
1. How to: embed text data  
2. How to: cache embedding results  
3. How to: create a custom embeddings class

### Vector stores
1. How to: use a vector store to retrieve data

### Retrievers
1. How to: use a vector store to retrieve data  
2. How to: generate multiple queries to retrieve data for  
3. How to: use contextual compression to compress the data retrieved  
4. How to: write a custom retriever class  
5. How to: add similarity scores to retriever results  
6. How to: combine the results from multiple retrievers  
7. How to: reorder retrieved results to mitigate the "lost in the middle" effect  
8. How to: generate multiple embeddings per document  
9. How to: retrieve the whole document for a chunk  
10. How to: generate metadata filters  
11. How to: create a time-weighted retriever  
12. How to: use hybrid vector and keyword retrieval

### Indexing
1. How to: reindex data to keep your vectorstore in-sync with the underlying data source

### Tools
1. How to: create tools  
2. How to: use built-in tools and toolkits  
3. How to: use chat models to call tools  
4. How to: pass tool outputs to chat models  
5. How to: pass run time values to tools  
6. How to: add a human-in-the-loop for tools  
7. How to: handle tool errors  
8. How to: force models to call a tool  
9. How to: disable parallel tool calling  
10. How to: access the RunnableConfig from a tool  
11. How to: stream events from a tool  
12. How to: return artifacts from a tool  
13. How to: convert Runnables to tools  
14. How to: add ad-hoc tool calling capability to models  
15. How to: pass in runtime secrets

### Multimodal
1. How to: pass multimodal data directly to models  
2. How to: use multimodal prompts

### Agents
1. How to: use legacy LangChain Agents (AgentExecutor)  
2. How to: migrate from legacy LangChain agents to LangGraph

### Callbacks
1. How to: pass in callbacks at runtime  
2. How to: attach callbacks to a module  
3. How to: pass callbacks into a module constructor  
4. How to: create custom callback handlers  
5. How to: use callbacks in async environments  
6. How to: dispatch custom callback events

### Custom
1. How to: create a custom chat model class  
2. How to: create a custom LLM class  
3. How to: create a custom embeddings class  
4. How to: write a custom retriever class  
5. How to: write a custom document loader  
6. How to: write a custom output parser class  
7. How to: create custom callback handlers  
8. How to: define a custom tool  
9. How to: dispatch custom callback events

### Serialization
1. How to: save and load LangChain objects

## Use cases

### Q&A with RAG
1. How to: add chat history  
2. How to: stream  
3. How to: return sources  
4. How to: return citations  
5. How to: do per-user retrieval

### Extraction
1. How to: use reference examples  
2. How to: handle long text  
3. How to: do extraction without using function calling

### Chatbots
1. How to: manage memory  
2. How to: do retrieval  
3. How to: use tools  
4. How to: manage large chat history

### Query analysis
1. How to: add examples to the prompt  
2. How to: handle cases where no queries are generated  
3. How to: handle multiple queries  
4. How to: handle multiple retrievers  
5. How to: construct filters  
6. How to: deal with high cardinality categorical variables

### Q&A over SQL + CSV
1. How to: use prompting to improve results  
2. How to: do query validation  
3. How to: deal with large databases  
4. How to: deal with CSV files

### Q&A over graph databases
1. How to: add a semantic layer over the database  
2. How to: construct knowledge graphs

### Summarization
1. How to: summarize text in a single LLM call  
2. How to: summarize text through parallelization  
3. How to: summarize text through iterative refinement

## LangChain Expression Language (LCEL)
1. How to: chain runnables  
2. How to: stream runnables  
3. How to: invoke runnables in parallel  
4. How to: add default invocation args to runnables  
5. How to: turn any function into a runnable  
6. How to: pass through inputs from one chain step to the next  
7. How to: configure runnable behavior at runtime  
8. How to: add message history (memory) to a chain  
9. How to: route between sub-chains  
10. How to: create a dynamic (self-constructing) chain  
11. How to: inspect runnables  
12. How to: add fallbacks to a runnable  
13. How to: pass runtime secrets to a runnable

## LangSmith

### Evaluation
1. (Linked in LangSmith evaluation how-to guides)

### Tracing
1. How to: trace with LangChain  
2. How to: add metadata and tags to traces
