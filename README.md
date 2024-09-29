# Sacrcasm_detection

In this sarcasm detection model, we:

  1. Tokenized and Padded: Converted text data into sequences of integers using a tokenizer, then padded them to a uniform length (max_len).
  2. Embedding Layer: An embedding layer is applied to map the tokenized words into dense vectors of size 50.
  3. LSTM Layer: An LSTM (Long Short-Term Memory) layer with 64 units was used to capture temporal patterns and dependencies in the text.
  4. Fully Connected Layer: A dense layer with 256 units was added, followed by ReLU activation to introduce non-linearity.
  5. Dropout: Dropout was applied at a rate of 0.2 to prevent overfitting by randomly turning off neurons during training.
  6.  Output Layer: A single neuron with sigmoid activation was added to output a probability for sarcasm detection (binary classification).

Model Evaluation: The model achieved an accuracy of ~80% with a loss of 0.40, indicating decent performance.
