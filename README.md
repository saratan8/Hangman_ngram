# Hangman_ngram

This project implements a Hangman word guessing game solver using N-gram language modeling. It simulates how a human might guess words intelligently by learning from a large word corpus.

## Overview

The solver predicts likely letters by calculating conditional probabilities from a training corpus of 250,000+ words. The goal is to minimize wrong guesses and solve the word as efficiently as possible.

## Files

- `hangman_api_user(2)(1).ipynb`: Main notebook that simulates the Hangman solver
- `words_250000_train.txt`: The training word list for the language model
- `Hangman Solver Description.pdf`: Documentation describing the algorithm and results
- `README.md`: Project description

## Core Concepts

- **N-gram language model**: Predicts the probability of each letter given partial word information
- **Pattern matching**: Filters possible words based on known/unknown letter positions
- **Entropy-based guessing**: Prioritizes letters that reduce uncertainty the most

## Example Use Case

- Word: `_ a _ _ _`
- Guessed letters: A, E, S, T
- Next letter prediction: likely R, based on N-gram frequency in the training set

## Outcome

The solver demonstrates how statistical language models can be applied to simple games like Hangman, bridging NLP concepts and interactive applications.

---
