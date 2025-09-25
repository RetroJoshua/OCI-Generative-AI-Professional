# LLM Intro Quiz: Questions and Answer Key

## Questions with Choices

### Q1: What best describes a language model in this module?

- A) A deterministic rule-based grammar engine
- B) A probabilistic model of text that outputs a distribution over a vocabulary given a prefix
- C) A database of sentences
- D) A speech recognition device

### Q2: When given a text prefix, what does a language model produce?

- A) A single best next word with no alternatives
- B) A distribution over the known vocabulary
- C) New words outside its vocabulary
- D) A sentence-level sentiment label

### Q3: In "Large Language Model", the term "large" primarily refers to:

- A) Dataset size
- B) Number of parameters
- C) Vocabulary size
- D) Number of layers must be exactly 12

### Q4: Which statement about vocabulary is TRUE?

- A) The model can assign probabilities to words it has never seen and that are outside its vocabulary
- B) The model only assigns probabilities to words in its known vocabulary
- C) The model generates probabilities only for the top 5 words
- D) Vocabulary is irrelevant to next-token prediction

### Q5: Which set captures the three main technical areas covered in the module?

- A) Data labeling, cloud deployment, monitoring
- B) Architecture, influencing distributions (prompting/training), decoding
- C) Speech-to-text, text-to-image, reinforcement learning
- D) Hardware acceleration, compilers, operating systems

### Q6: Which method influences model outputs WITHOUT changing parameters?

- A) Pretraining
- B) Fine-tuning
- C) Prompting
- D) Distillation

### Q7: Which method DOES change model parameters?

- A) Prompting
- B) Decoding
- C) Training
- D) Tokenization

### Q8: What is "decoding" in the context of LLMs?

- A) Compressing the model weights
- B) Generating text from the model's probability distribution
- C) Translating between languages
- D) Encrypting outputs for privacy

### Q9: What is the stated purpose of the module?

- A) A deep-dive exclusively for experts
- B) An introductory, accessible overview with slightly deeper technical depth than mainstream coverage
- C) A tutorial on deploying GPUs in the cloud
- D) An advanced course on speech recognition

### Q10: Which statement is FALSE regarding "large" in LLMs?

- A) There's no universal threshold for what counts as "large"
- B) "LLM" is often used loosely, sometimes even for models like BERT
- C) "Large" always means more than 100B parameters
- D) The term often correlates with models used for text generation

### Q11: For the prompt "They sent me a --" what does the model compute?

- A) A grammar tree only
- B) A probability for each word in its vocabulary filling the blank
- C) An image representing the next scene
- D) A deterministic word without alternatives

### Q12: After the introduction, what topic does the module dive into next?

- A) Tokenization
- B) Optimization algorithms
- C) LLM architectures
- D) Deployment pipelines

### Q13: Decoding uses vocabulary distributions to produce:

- A) Images and audio
- B) Only short phrases
- C) Structured database rows
- D) Sentences, paragraphs, and documents

### Q14: Which statement correctly contrasts prompting and training?

- A) Prompting updates model weights; training does not
- B) Training never affects outputs
- C) Both prompting and training update weights
- D) Prompting does not update weights; training does

### Q15: In the module, the "numbers under the words" refer to:

- A) Character counts
- B) Corpus frequency ranks
- C) Probabilities assigned to each token
- D) Embedding vector dimensions

### Q16: Which statement about LLMs vs. "normal" language models is accurate?

- A) LLMs use a completely different paradigm from language models
- B) LLMs are no different in kind; "large" refers (loosely) to parameter count
- C) LLMs only perform translation
- D) LLMs cannot generate text

### Q17: Which action is outside the scope of prompting?

- A) Providing task instructions in the input
- B) Supplying examples within the prompt
- C) Changing model weights during inference
- D) Clarifying constraints and desired format

### Q18: Which topic is explicitly listed as an extension/use area after the three core topics?

- A) Novel applications in academic and industrial research
- B) Quantum computing implementation details
- C) Mobile app development patterns
- D) Computer vision object detection

### Q19: Who/what computes the probability distribution over the vocabulary?

- A) The input preprocessor
- B) The language model
- C) The dataset curator
- D) The operating system

### Q20: What is the primary goal of decoding?

- A) Convert token probability distributions into coherent text sequences
- B) Measure training loss
- C) Compress the vocabulary
- D) Evaluate GPU memory usage


## Answer Key (Table)

| # | A | B | C | D |
|---|---|---|---|---|
| 1 |  | x |  |  |
| 2 |  | x |  |  |
| 3 |  | x |  |  |
| 4 |  | x |  |  |
| 5 |  | x |  |  |
| 6 |  |  | x |  |
| 7 |  |  | x |  |
| 8 |  | x |  |  |
| 9 |  | x |  |  |
| 10 |  |  | x |  |
| 11 |  | x |  |  |
| 12 |  |  | x |  |
| 13 |  |  |  | x |
| 14 |  |  |  | x |
| 15 |  |  | x |  |
| 16 |  | x |  |  |
| 17 |  |  | x |  |
| 18 | x |  |  |  |
| 19 |  | x |  |  |
| 20 | x |  |  |  |
