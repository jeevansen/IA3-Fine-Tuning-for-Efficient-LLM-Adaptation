# IA-Fine-Tuning-for-Efficient-LLM-Adaptation
Implementation of IA³ (Infused Adapter by Addition) for efficient fine-tuning of large language models. Trains lightweight scaling vectors instead of full weights, reducing parameters and compute while maintaining strong accuracy. Compatible with Hugging Face PEFT and Transformers.
Key Features:

Implements IA³ fine-tuning for llama8b.

Reduces fine-tuning memory and compute costs.

Maintains near full fine-tuning accuracy with <1% of total parameters updated.

Compatible with Hugging Face Transformers and PEFT libraries.

Example notebooks for NER, classification, and instruction-tuning tasks.
