# DIRLLLM

DIRLLLM, or Database Information Retrieval using Lightweight LLM, is a project that aims to facilitate local information retrieval or management on structured databases (which typically require knowledge of SQL) using natural language by generating the appropriate SQL query from the instruction using a small, distilled model.


Contents:


teacher_model.ipynb: Fine-tuning of the T5-base model with sql datasets.

knowledge_distillation_llm.ipnyb: Distillation of knowledge from teacher to student.

Presentation.ipynb: A notebook for running and testing the distilled model.

confidence_score.ipynb: Additional notebook with added confidence checking to improve query executability 

Dirllm_web_app.ipynb: Notebook used to host the corresponding Anvil web app.
