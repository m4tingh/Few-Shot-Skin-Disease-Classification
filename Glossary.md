1. **Meta Learning**: Meta-learning, also known as "learning to learn", is a paradigm where a model learns how to adapt to new tasks quickly — by observing how to learn across many tasks. Instead of just training on one fixed task, the meta-learner gathers knowledge about *how* learning itself works.

2. **Padding**: Padding is used to make all input sequences the same length by adding dummy values (usually zeros) to shorter ones.
Example:
["hello", "world"] → ["hello", "world", 0, 0]

3. **Embedding**: Embedding maps words or labels into dense numeric vectors that capture meaning and similarity.
Example:
"cat" → [0.2, 0.7, -0.4]
"dog" → [0.2, 0.7, -0.5]

4. **Few-Shot Learning (fsl)**: Few-shot learning is a learning paradigm where models are trained to recognize new classes using only a few labeled examples per class.
It’s useful when collecting large amounts of data is difficult, like in medical imaging.
Example: Classifying skin diseases using only 1–5 samples per type.

5. **Task-invariant Embedding Model**: A model that generates embeddings (vector representations) which work well across multiple tasks without retraining.
It learns general features of data, making it adaptable to new tasks quickly.
Essential for meta-learning where fast adaptation with few examples is needed.

6. **Latent Space**: A hidden, compressed representation space where raw data (like images or text) is mapped into simpler forms (vectors).
In this space, important features and patterns are captured, making it easier for models to understand and process data efficiently.