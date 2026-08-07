# Contoso Sales Analytics: In-Memory Tabular Foundation Models via Tool Calling

This lab demonstrates how to pair **TabPFN** with **`ellmer`** to create an automated sales analytics co-pilot in R.

## Key Concepts
- **Tool Calling with R Objects**: Passes string names of in-memory data frames (`train_df`, `test_df`) to keep LLM context payloads light and bypass serialization limits.
- **Tabular Foundation Models (TFMs)**: Uses TabPFN for instant zero-shot supervised classification without explicit model tuning or traditional training loops.

## Tech Stack
- **R / Tidyverse**: Data manipulation and feature prep
- **`tabpfn`**: Tabular Foundation Model engine
- **`ellmer`**: Unified R interface for LLM interaction and tool registration
- **`ollama/gemma4`**: Local LLM execution