# Hello Universe
Exploring Astronomy Word Associations with Small Language Models

## Changes 
- Reorganized into the Hello Universe tutorial structure: Learning Goals, Introduction, Imports, numbered tutorial sections, FAQ, About this Notebook, and Citations.
- Preserved the astronomy Codenames idea while making the notebook more educational and self-contained.
- Added a robust embedding wrapper that uses `sentence-transformers` when available and falls back to local TF-IDF.
- Added scoring functions for target similarity, separation margin, and assassin/risk penalty.
- Moved the small generative language model into an optional extension so the main notebook does not require a large model download.
- Added exercises and reviewer-facing explanations of limitations.

