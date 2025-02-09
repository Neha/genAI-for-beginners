## Tokens

In GenAI world, no one understand any text or word. In GenAI, it is just numbers.

Every text will be break into tokens. These tokens are very important as 
the drive the cost of your app. More tokens usually mean higher processing costs. 

1. Tokens are the raw text units that a model processes. 

2. A token is a single unit of text

3. They are the building blocks of the input and output.

 This can be a word, a part of a word, or even a single character, depending on how the text is tokenized. Tokenization is the process of breaking down a string of text into these smaller units or tokens.

**Example:**

1. Input: hello -> 1 token

2. Input: good morning -> 3 token

3. Input: "What is the color of the sky?" -> 12 tokens 

   Output: "color of sky is blue" -> 9 tokens

So, you will be charged for the number of tokens getting used.

If there is an input then think in tokens, and similarly the output would be too in tokens.

### cost calculation

Every LLMs has their price model based on the tokens. So, read the documentation and pricing of the LLMs you 
will be using.

