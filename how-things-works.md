## How things works (under the hood)

In GenAI, we can do text, and images. Now, we will first take the example of text.

With text what we can do?

1. Next text prediction

2. Translation

3. Summarisation

4. Chat


To do any of the above, we can take any approach we discussed in the LLMs introduction. In this section, we will go one-by-one for each:

1. Pre-trained models:

a. pick any foundational model

b. Context window. It will take the user's input

c. LLMs will understand and try to predict the best possible next word

d. share the outout with user.

The main work is happening at step c. How the LLMs are able to predict the next word? If you are interersted in this then this section is for you


LLMs are trained on large data. It is supervised and unsupervised learning. A small example:

Input: This 
Output: This is

Input: This is 
Output: this is a 

Input: This is a
Output: This is a house

The above is just an example. Imagine doing this for billions of combination and traing the data. Once these LLMs are trained now basis of the input they will give the output.

But here are a few questions might be coming in your mind


1. Who trains them?
Companies, researchers, etc

2. who evaluate the i/p and o/p is correct or not?

3. how to check accuracy

4. what if soemthing goes wrong

5. what about the context of the conversation

6. Edge cases?

If you had these questions, then congrats you are thinking in the right direction.

Let's explore these one by one:

There is a long journey between input and output. When I say long journey, it means there is a LOT goes behind the
undertanding Input and giving output and in that all the magic and logical things are.

LLMs are based on the algos and maths. Here all the papers will come handy. PS: read these if you want to go all deep dive. Other wise you can read the summary I added in the column section or ask ChatGPT to summaris for you :) 

These algos are responsible for predicting, and mainting context. Read "focus is all you need".


