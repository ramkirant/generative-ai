# Generative AI

## Precursors

### What is Artificial Intelligence?

Artificial Intelligence is a broad field of computer science that focuses on creating intelligent systems capable of performing tasks that typically require human intelligence. 

### What are the different types of AI Systems

- Conventional AI Systems (Discriminative)

  Conventional AI Systems trains by learning from a set of input data and performs predictions. 
  
- Generative AI Systems (Generative)

  Generative AI Systems needs tremendous amounts of input data. Based upon the training data, using the neural networks behind the scenes, Generative AI systems would be able to generate new content.
  
### How would machines be able to perform tasks that require human intelligence?

Machines would be able to perform these tasks by leveraging **Machine Learning**

### What is Machine Learning?

Machine learning is a subset of AI that focuses on development of algorithms or models that enable computers to learn and make predictions or decisions without explicit programming. 

### What is needed for a machine to learn?

- Huge sets of Training Data
- High Computational Power
- Optimized and Resilient Training Algorithms.

### What are the different variants of Machine Learning?

- Deep Learning

### What is Deep Learning?

Deep Learning is a subset of Machine Learning that learns using the concept of neurons of a human brain. Deep Learning leverages Neural Networks to process data. Neural Network is a network of multiple machines where the data is passed from one layer of machines to another. Each layer of machines processes the data and sends it to the next layer for further processing. Neural Networks need a lot of computational power which is the reason for a resistance to adopt them during the early days. Recently, this computational power is made easily available. GPUs have become much cheaper and have become more affordable. This made adoption of Neural Networks for various Deep Learning use cases easy.

*Deep Learning is a subset of Machine Learning*

*Machine Learning is a subset of Artificial Intelligence*

## ChatGPT

### What is ChatGPT?

ChatGPT is a large language model (LLM). It is designed with natural language understanding and generation. It can handle a conversational context. It remembers the background of a conversation.

- It is a Generative AI application
- Developed by OpenAI
- Trained on billions of documents
- Based on Generative Pre-Trained Transformer (GPT) architecture, a type of neural network. 
- It offers Web Interface for end-users and API for developers. 

## Generative AI

### Where does Generative AI fits into this Artificial Intelligence Landscape?

Generative AI is a subset of Deep Learning. It uses Deep Learning Neural Networks to learn from the Training Data and generate new content from it. 

Generative Artificial Intelligence (Gen AI) is a type of AI that can create new content, such as audio, images, text, code, videos etc. 

### Key Terminologies of Generative AI

- LLM
- Prompt Engineering
- Embeddings
- Fine Tuning

### Large Language Models (LLMs)

LLMs are powerful artificial intelligence models that are designed for understanding and generating human-like text. 

People usually use the words Generative AI and LLMs interchangeably, but they are not the same. Generative AI generates all types of content ranging from Text, Image, Audio, Video, Code Snippets etc. LLM is a subset of GenerativeAI and is used only to generate text.

The brains behind LLM is a neural network called Transformer. Transformer is very good at understanding human language, words, sentences and context. 

#### Key Points of LLM
- Pre-Trained: LLMs are trained on a huge corpus of data. 
- Size and Scale: LLMs use massive neural networks called transformers, and they contain billions of parameters. Parameters are like variables that are used to train the model. Higher the number of parameters, better is the model, training, understanding and generation. 
- Fine-Tuned: More targeted training for specific tasks. 

#### Use cases for LLM
- Content Generation - Marketing, advertising
- Chatbots and virtual assistants - User Support, Interactions
- Language translation - expand communication
- Text summarization - reduce lengthy text
- Q&A - The most prominent use case

#### Limitations of LLMs
- Finite Training Data
  
  LLMs even though they got trained on large training set, they are trained on finite training data and they might not be up to date with latest updates or information.

- Stochastic Nature

  LLMs are stochastic (random) due to random initialization, noisy training data and complex computations. There is a high probability for their output to be not correct.

- Plausible sounding but incorrect answers

  As said above, the output from LLMs can be incorrect

### Prompt Engineering
Prompt is a specific question, command or an input that we provide to an AI system to request a particular response, information or action. 

#### Examples of Prompt Engineering
- Text Generation

  Summarize the key points of this research article and its impact on the industry.
- Creative Writing
  
  Write a short story about a detective solving a robbery case. 
- Image Generation
  
  Generate an image of a yellow car on a countryside road.
- Code Generation

  Write a python code to input two numbers and calculate their sum

#### Best Practices for Prompt Engineering
- Clearly convey the desired response
- Provide context or background information. For Example, if you are from health care industry, and you want to know about AI, give a prompt like "I am from health care industry. Explain AI in the context of health care industry."
- Balance simplicity and complexity. If you keep your prompt simple, then LLM will give you a very generic answer. If we include 10 things in our prompt, LLM might get confused and give us vague answers. It is important to maintain a good balance between simplicity and complexity.
- Iterative testing and refinement. We might not get the right answer in the first prompt. Keep changing the prompt until we get our desired response. 

### Embeddings
Embeddings is a concept of converting text to numbers for machine to understand and generate the required output. 

Embeddings are numerical representation of text. They are essential for AI models to understand and work with human language effectively. 

When we give a prompt to a LLM, it would first do something called as "chunking the words". It would break the prompt into its individual words. For each word, it would assign a set of numbers called embeddings. These numbers provide meaning, context, connections to each and every word of the sentence. Embeddings are generated by passing the words through the neural network. Neural networks being trained on millions of data points would then convert these words into embeddings.  

### Fine Tuning
Fine-tuning a LLM is the process of adapting a pre-trained model to perform specific tasks or to cater to a particular domain more effectively. There are three ways to fine tune a model. 

- Self Supervised 
  
  We provide domain specific training data to our model and our model will learn from it. This is very similar to generic training with domain specific data fed to the model.

- Supervised

  We provide a labeled data set (both input and output) and the model will learn from it. 

- Reinforcement

  Reinforcement is an old concept. We feed training data to our model and grade its out. If the output is accurate, we give it a high score, if not, we give it a low score. Over time, the model will adapt to provide correct output based on the grades we provide.

#### Fine-Tuning is not about: 
- Creating intelligence from scratch. We start from a foundation model which is already trained on a large data set of data, and we fine tune it as per need.
- Eliminating data requirements. 
- A single universal solution.
- Magical one-time process.

### Use cases of Gen AI across industries
#### Software Development

| Use Case              | Details                                                                                                    | Benefits                                                                                                 |
|-----------------------|------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Build                 | Generate code from Scratch. <br/> Fix errors.<br/> Optimize performance. <br/>Direct integration with IDEs | Reduce manual effort. <br/>Cross-enable developers. <br/>Better code practise.<br/>Document details.     |
| Testing               | Identify test scenarios. <br/>Write detailed test cases.<br/>Generate automation scripts.                  | Reduce scenario misses. <br/>Identify edge cases. <br/>Reduce manual effort. <br/>Expedite testing cycle |
| Requirement Gathering | Generate Epics. <br/>Generate User Stories. <br/>Generate Acceptance Criteria.                             | Ensure coverage & identify edge cases. <br/>Reduce manual effort. <br/>Expedite the cycle                |
| Documentation         | Requirement docs. <br/>Test Reports. <br/>User Guides / Operational docs.                                  | Reduce manual effort. <br/>Ensure proper documentation. <br/>Meet regulatory and organization needs.     |

