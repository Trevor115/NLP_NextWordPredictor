# NLP_NextWordPredictor
A small Python program that learns trigram probabilities from text and uses them to predict the most likely next word. It can also generate short sequences of text based on the learned model.

# Features
- Preprocesses text (lowercasing, punctuation removal, tokenization)
- Builds trigram counts and probabilities
- Predicts the top next‑word candidates for any two‑word context
- Generates text by repeatedly choosing the highest‑probability next word
- Includes helper functions for printing counts and probabilities

# How It Works
The program counts how often each trigram appears, converts those counts into probabilities, and uses them to make predictions.
