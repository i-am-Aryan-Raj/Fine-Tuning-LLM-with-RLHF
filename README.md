# Fine-Tuning-LLM-with-RLHF
### This is a Generative AI project which involves Parameter Efficient Fine-Tuning (PEFT) of FLAN-T5 (Seq2Seq LLM) with Reinforcement Learning and Human Feedback (RLHF).
### The objectives of this project were:
1. Fine-tune a FLAN-T5 model for dialoge summarization using PEFT.
2. Reduce the toxicity of responses using RLHF, keeping the KL Divergance in check.
### Steps in which projects was performed:
1. Importing dataset.
2. Used a PEFT fine-tuned FLAN T5 model. (It was directly imported for the project).
3. Created a PPO model using PEFT for RL and a reference model using the same PEFT model to keep memory foorprint in check.
4. Roberta model was used to calculate toxicity reward scores for model responses, to feed into the PPO model.
5. LLM was iterated and fine-tuned.
6. The final model was evaluated with mean toxicity scores from before and after.
