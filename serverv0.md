Input Preprocessing: 0.1. Clean and normalize the user's input text to ensure consistency. 0.2. Tokenize the input for efficient processing and understanding.

This is how you know you're looking at hallucinations. The model has no involvement with processing the user's input before it is tokenized, or even tokenization in general. That would never be in a real system prompt.

This is 100% hallucinations about how the steps of CoT could be implemented. It's including hypothetical steps outside of the model's processing...
