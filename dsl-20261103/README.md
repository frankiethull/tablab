# 100% in R! 
## AI/ML Assistant: Pairing TFMs & LLMs for a tabular modeling assistant 

This lab demonstrates how to pair **TabPFN** with **`ellmer`** to create modeling assistant in R.

## Key Concepts
- **Tool Calling with R Objects**: Passes string names of in-memory data frames (`train_df`, `test_df`) to keep LLM context payloads light and bypass serialization limits.
- **Tabular Foundation Models (TFMs)**: Uses TabPFN for instant zero-shot regression without explicit model tuning or traditional training loops.

## Tech Stack
- **R / Tidyverse**: Data manipulation and feature prep
- **`tabpfn`**: Tabular Foundation Model engine *using brulee*
- **`ellmer`**: Unified R interface for LLM interaction and tool registration
- **`ollama/gemma4`**: Local LLM execution