# Arabic Spell Checker with NLP Integration

## Overview

This project is an **Arabic Spell Checker** designed to detect and correct misspelled words in Arabic text using Natural Language Processing (NLP) techniques. The system incorporates two primary models, **Levenshtein Distance** and **n-gram**, to provide more accurate and context-sensitive spelling corrections. The application supports basic typo corrections as well as more advanced context-aware adjustments.

## Features

- **Two Spell-Checking Models**:
  - **Levenshtein Distance**: Detects minor typographical errors like insertions, deletions, and substitutions, and provides multiple correction options.
  - **N-gram Model**: Uses bigrams and trigrams to provide context-aware corrections by analyzing word sequences.
  
- **NLP Techniques Used**:
  - **Tokenization**: Breaks down sentences into words (tokens) for further processing.
  - **Stemming**: Reduces words to their root form for consistent text analysis.

- **Graphical User Interface (GUI)**:
  - Developed with Tkinter for easy user interaction.
  - Users can input Arabic text, check for spelling errors, and receive correction suggestions.

- **Customizable Spell-Checking**:
  - Choose between Levenshtein Distance and n-gram models for error correction.
  - Displays multiple correction options based on context and similarity.


