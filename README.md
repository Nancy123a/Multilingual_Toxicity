# Multilingual_Toxicity
Jigsaw Multilingual Toxic Comment Detection

The goal is to build a model capable of predicting the likelihood that a comment is toxic, with toxicity represented by a value of 1.0 and non-toxicity by 0.0. The data provided includes comments from Wikipedia talk pages and the Civil Comments platform, with a mixture of English and non-English text.

1) Data Files:
    - Training Data:
    jigsaw-toxic-comment-train.csv: Contains English comments sourced from Wikipedia talk pages. Each comment is labeled as either toxic or non-toxic.
    - Validation Data:
    validation.csv: Consists of comments in various non-English languages, sourced from Wikipedia talk pages. This file is used to validate model performance.
    - Test Data:
    test.csv: Includes comments from Wikipedia talk pages in multiple non-English languages. Participants need to predict the toxicity of these comments. The true labels are provided 
    in test_labels.csv after the competition ends.
2) Key Columns:
   - id: A unique identifier for each comment.
   - comment_text: The actual text of the comment to be classified.
   - lang: The language in which the comment is written.
   - toxic: A binary label indicating whether the comment is toxic (1) or not (0). This label is not available in the test set but is included in the training and validation datasets.
3) This notebook provides a comprehensive exploration of Recurrent Neural Networks (RNNs) and advanced deep learning architectures for Natural Language Processing (NLP). The content includes:
   - Simple RNNs: Introduction to basic RNN structures.
   - Word Embeddings: Explanation of word embeddings and methods to obtain them.
   - LSTMs: Overview of Long Short-Term Memory networks for handling long-range dependencies.
   - GRUs: Introduction to Gated Recurrent Units, a simplified version of LSTMs.
   - Bi-Directional RNNs: Using RNNs that process sequences in both directions.
   - Encoder-Decoder Models (Seq2Seq): Foundation of sequence-to-sequence models for tasks like translation.
   - Attention Models: Discussion on attention mechanisms to enhance model focus.
   - BERT: Exploration of Bidirectional Encoder Representations from Transformers.


