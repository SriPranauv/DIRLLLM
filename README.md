# DIRLLLM

DIRLLLM, or Database Information Retrieval using Lightweight LLM, is a project that aims to facilitate local information retrieval or management on structured databases (which typically require knowledge of SQL) using natural language by generating the appropriate SQL query from the instruction using a small, distilled model.


Contents:


Teacher_model.ipynb: Fine-tuning of the T5-base model with SQL datasets. (An identical approach is used for the initial fine-tuning of the Student model.)

Knowledge_distillation_llm.ipynb: Distillation of knowledge from teacher to student.

Confidence_score.ipynb: Additional notebook with added confidence checking to improve query executability 

Web_app_backend.ipynb: Notebook used to host the corresponding Anvil web app and present/test the model.
