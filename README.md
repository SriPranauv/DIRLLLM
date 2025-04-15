# DIRLLLM

DIRLLLM or Database Information retrival using Lightweight LLM, is a project that aims to facilitate local information retrival or management on strutured data bases (which typically require knowledge of SQL) using natural language by generating the appropirate SQL query from the instruction using a small size, distilled model.

Contents:

teacher_model.ipynb: Fine-tuning of the T5-base model with sql datasets.
knowledge_distillation_llm.ipnyb: Distillation of knowledge from teacher to student.
Presentation.ipynb: A notebook for running and testing the distilled model.
confidence_score.ipynb: Additional notebook wiht added confidence checking to improve query executablity 
Dirllm_web_app.ipynb: Notebook for hosting the corresponding Anvil webapp.
