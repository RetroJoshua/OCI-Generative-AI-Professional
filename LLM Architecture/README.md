### LLM Architectures: Encoders vs. Decoders

*   **Two Major Architectures:** The lesson focuses on two primary architectures for large language models (LLMs): encoders and decoders.
*   **Core Capabilities:** These architectures correspond to two distinct model capabilities:
    *   **Embedding:** Converting a sequence of words into a single vector or a sequence of vectors, capturing the text's semantics.
    *   **Text Generation:** Taking an input sequence of words and producing a generated sequence of words.
*   **Transformer Foundation:** Both encoders and decoders are built upon a fundamental building block called a transformer, popularized by the 2017 paper "Attention Is All You Need."
*   **Encoder Models:**
    *   **Purpose:** Designed to encode text, producing embeddings.
    *   **Functionality:** Take a sequence of words and generate a vector representation for each word and the entire sentence.
    *   **Applications:** Primarily used for tasks like classification, regression, and vector/semantic search (e.g., retrieving similar documents from a corpus).
*   **Decoder Models:**
    *   **Purpose:** Designed to decode or generate text.
    *   **Functionality:** Take a sequence of tokens and emit the next token in the sequence based on computed probabilities. They produce one token at a time but can be invoked repeatedly for longer sequences.
    *   **Examples:** Cohere command model, GPT-4, Llama.
    *   **Applications:** Highly capable in generating fluent text, answering questions, and participating in dialogue.
    *   **Note:** Typically not used for embedding; encoders are preferred for that task.
*   **Encoder-Decoder Models:**
    *   **Construction:** Combine an encoder and a decoder, essentially "gluing" them together.
    *   **Applications:** Primarily utilized for sequence-to-sequence tasks, such as translation. The encoder embeds the input, and the decoder then generates the output sequence one token at a time, with generated tokens fed back into the decoder.
*   **Model Size:**
    *   **Definition:** Refers to the number of trainable parameters a model possesses.
    *   **Observation:** Decoder models tend to be significantly larger than encoders, historically, though recent research suggests smaller models might achieve fluent text generation with cleverness.
*   **Task-Specific Selection:** Different styles of models are deliberately chosen to accomplish various tasks, although, in theory, any model could be used for any task, it may not be appropriate in practice.