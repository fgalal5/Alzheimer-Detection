# Notebooks
 
Developed a three-branch late-fusion system for automatic Alzheimer's disease detection from the DementiaBank Cookie Theft picture-description task, combining TF-IDF lexical features, HuBERT acoustic representations, and GPT-4o-mini scene-graph scoring. The final system achieved AUROC 0.9257 and F1 0.8537 on held-out test data, with statistically significant improvements over the TF-IDF baseline.
The notebooks are preserved with outputs where useful for project traceability.
They are numbered by role/history rather than treated as a clean production
pipeline.

| Notebook | Purpose |
| --- | --- |
| `00_original_course_notebook.ipynb` | Original exploratory course notebook. |
| `01_colab_run_all.ipynb` | Early Colab workflow for baseline experiments. |
| `02_colab_final_run.ipynb` | Final Colab workflow snapshot. |
| `03_colab_full_final_run.ipynb` | Full final Colab workflow with optional LLM sections. |
| `04_colab_run_final_final.ipynb` | Most complete Colab packaging workflow, including later optional scene/event experiments. |
| `05_submission_ready_colab.ipynb` | Clean submission runner with required final pipeline, optional experiment inventory, summary display, and packaging cells. |

Do not commit notebooks containing pasted API keys or raw protected participant
content. The checked-in notebooks use placeholders such as `OPENAI_API_KEY` and
do not include actual keys from the audit performed during cleanup.
