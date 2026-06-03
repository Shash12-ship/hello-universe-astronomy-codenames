# Hello Universe Notebook Submission 

## Notebook title
Exploring Astronomy Word Associations with Small Language Models

## Files
- `Exploring_Astronomy_Codenames_with_Language_Models.ipynb` — clean source notebook with no execution outputs.
- `Exploring_Astronomy_Codenames_with_Language_Models_executed.ipynb` — executed notebook with plots/tables generated using the local fallback backend.
- `Exploring_Astronomy_Codenames_with_Language_Models.html` — rendered preview for quick review.
- `requirements.txt` — package list for reproducing the notebook.
- `submission_cover_email_draft.txt` — draft email to STScI/MAST Hello Universe.

## What changed from the prototype
- Reorganized into the Hello Universe tutorial structure: Learning Goals, Introduction, Imports, numbered tutorial sections, FAQ, About this Notebook, and Citations.
- Preserved the astronomy Codenames idea while making the notebook more educational and self-contained.
- Added a robust embedding wrapper that uses `sentence-transformers` when available and falls back to local TF-IDF so the notebook can still execute in restricted environments.
- Added clearer scoring functions for target similarity, separation margin, and assassin/risk penalty.
- Moved the small generative language model into an optional extension so the main notebook does not require a large model download.
- Added exercises and reviewer-facing explanations of limitations.

## Items to edit before submission
- Replace `[Add second author name]` with the actual second author name.
- Confirm final affiliations.
- Confirm whether STScI wants the executed notebook, clean notebook, or both.
- If a strict dependency environment is requested, decide whether to keep the fallback backend or require `sentence-transformers` as the primary backend.

## Suggested submission note
This is a lightweight educational notebook. It does not depend on a large astronomy dataset; instead, it introduces semantic embeddings and small-language-model behavior through astronomy vocabulary. A natural future extension would connect the board/clue vocabulary to MAST metadata, HLSP documentation, or mission-specific object classes.
