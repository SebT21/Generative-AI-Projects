# Gollum Chatbot: A Character-Driven Conversational AI

This repository contains the code and report for a project completed as part of the **ECE1724 Artificial Intelligence** course during my Master's in Engineering (MEng) at the **University of Toronto**. The project involved creating a chatbot modeled after Gollum from *The Lord of the Rings*, leveraging natural language processing (NLP) techniques to replicate the character’s unique speech patterns and personality.

## Project Objective

The goal of this project was to develop a chatbot that mimics the speech style and personality of Gollum, exploring the potential of AI in generating character-specific dialogue. This was achieved using the **DialoGPT** model fine-tuned on a curated dataset of Gollum's dialogues.

## Features

- **Character-Specific Dialogue**: Fine-tuned the DialoGPT model to capture Gollum's unique speech patterns, including his fragmented sentences and use of terms like "precious."
- **Data Preprocessing**: Curated and cleaned datasets, combining Gollum's lines from *The Lord of the Rings* movies and generated lines to enrich conversational scope.
- **System Architecture**: Implemented a dialogue system comprising input processing, context management, and output generation to ensure coherent and character-specific responses.

## Contributions

- **Model Fine-Tuning**: Preprocessed and prepared data, fine-tuning DialoGPT for character-specific dialogue generation with a focus on Gollum's syntax and semantics.
- **System Design**: Designed and implemented the chatbot's architecture, including context-aware response handling and user input processing.
- **Report Writing**: Authored the report, documenting the project's methodology, results, and insights.

## Results

- Successfully captured the style of Gollum's speech, including quirks like fragmented sentences and self-referential language.
- Demonstrated improvements in response quality with increased training epochs and context lines, reflected by reduced perplexity scores.
- Identified challenges such as input padding issues that affected response accuracy, offering areas for future refinement.

## Challenges

- **Data Collection**: Limited availability of Gollum-specific dialogues required creative solutions, such as combining original lines with AI-generated data.
- **Technical Constraints**: Training and testing were conducted on a CPU setup, which slowed the process and limited dataset size.
- **Padding Issues**: Input padding caused inconsistencies in response accuracy, highlighting an area for further debugging and optimization.

## Repository Contents

- **`Code.ipynb`**: Python scripts for data preprocessing, model training, and chatbot implementation.
- **`Gollum Chatbot Report.pdf`**: The comprehensive project report documenting the development process and findings.

## Future Work

1. Expand the dataset to include more dialogues for a richer conversational scope.
2. Resolve the input padding issue to improve response accuracy.
3. Integrate voice synthesis and visual elements for an immersive user experience.
4. Explore the potential of applying this approach to other fictional or historical characters.
