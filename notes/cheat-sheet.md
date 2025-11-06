## Cheat Sheet 

Learning AI/GenAI is also about learning all the abbreviations. If you are starting, then there would be the time when 
you have to look back to see what is what.

This is a cheat sheet to do a qucik revision:

| Term | Full Form | Description |
|----------|----------|----------|
| AI   | Artifical Intelligance   |  Artifical Intelligance is the stream of the computer science that focused on creating system that can perform tasks that typically require human intelligence   |
| GenAI   | Generative Artifical Intelligance   | Generative AI is a subset of artificial intelligence focused on creating new content, such as text, images, music, and more, rather than merely analyzing existing data.   |
| LLMs   | Large language Models   | LLMs are the pre-trained models available to be used by users. They mainly focused on the text   |
| RAG   | Retrival Augumented Generation  | RAG is a method that combines the strength of information retrival systems and generative models to improve the quality and relevance of generated content.   |
| AGI   | Artifical Generation Intelligence   | -   |
| FM   | Foundational Models   | Foundational Models that are available pre-trained but go beyond the text.   |
| token   | -   | AI doesn't understand words. Words converts to numbers and those numbers are tokens. Tokens decides the cost of the project. Eg: good morning word would be 2 tokens    |
| context window   | -   | maximum amount of tokens (text) a model can process at a given time while processing or generating text.   |
| Fine tunning   | -  | A way to tune the LLMs more and better for a specific task   |
| Temperature   | -   | A number used to tune the degree of randomness   |
| top-k   | -   | A number used to pick the top results   |
| top-p   | -   | A numebr used to predict next    |
| Encoder &  Decoder | -   | -   |
| LangChain  | -   | Langchain a framework for creating GenAI apps   |
| Hallunication  | -   | When AI starts start made up content   |
| Transformers  | -   | Algorithims use for the LLMs   |
| Prompt engineering  | -  | designing & refining the inputs for the LLMs such as ChatGPT to get the optimize, and performant output   |
| Embeddings  | -  | Emeddings are the numerical representations of the data.  typically used to convert categorical data, such as words or images, into continuous vectors in a high-dimensional space. These vectos captures the relationship and semantic meaning. |
| vectorDB  | -  | VectorDB are the special designed to store, index, and query high-dimensional vectors efficiently (embeddings)   |


### LLMs vs FMs
while all large language models can be considered foundational models within the context of language, not all foundational models are large language models. Foundational models represent a broader concept that includes multi-modal and general-purpose models.

In AI fundamentals difference between LLMs and FMs is important:

1 . LLMs are general purpose or FMs?

2 . LLMs are specialied or FMs?

### temperature
tempertaure is a hyperparameters (value between 0-1) which helps in setting the model's output creativeness. Example: 0 means very strict and low creativeness (means low chances of hallucination), 1 means model's output will be more align to being creative and can create hallucinatied results. 

### top-k
top-k limits the number of next quality output token

### top-p
top-p limits the percentage of next quality output token

