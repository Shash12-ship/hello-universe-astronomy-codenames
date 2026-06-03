# Hello Universe Notebook Submission Packet

## Notebook title
Exploring Astronomy Word Associations with Small Language Models

## Files
- `Exploring_Astronomy_Codenames_with_Language_Models.ipynb` — clean source notebook with no execution outputs.
- `Exploring_Astronomy_Codenames_with_Language_Models_executed.ipynb` — executed notebook with plots/tables generated using the local fallback backend.
- `Exploring_Astronomy_Codenames_with_Language_Models.html` — rendered preview for quick review.
- `requirements.txt` — package list for reproducing the notebook.
- `submission_cover_email_draft.txt` — draft email to STScI/MAST Hello Universe.

## Changes 
- Reorganized into the Hello Universe tutorial structure: Learning Goals, Introduction, Imports, numbered tutorial sections, FAQ, About this Notebook, and Citations.
- Preserved the astronomy Codenames idea while making the notebook more educational and self-contained.
- Added a robust embedding wrapper that uses `sentence-transformers` when available and falls back to local TF-IDF so the notebook can still execute in restricted environments.
- Added clearer scoring functions for target similarity, separation margin, and assassin/risk penalty.
- Moved the small generative language model into an optional extension so the main notebook does not require a large model download.
- Added exercises and reviewer-facing explanations of limitations.

