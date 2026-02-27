# Tiny Stories Small Language Model (SLM)

## Objective
Build a 2M parameter Small Language Model capable of generating coherent children's stories.

## Dataset
TinyStories dataset from HuggingFace  
Source: https://huggingface.co/datasets/roneneldan/TinyStories

## Model Architecture
- GPT-style Transformer
- 6 Layers
- 6 Heads
- 384 Embedding size
- ~2.1M parameters

## Training
- Tokenization: tiktoken (GPT-2)
- Optimizer: AdamW
- Scheduler: Linear Warmup + Cosine Decay
- Mixed Precision Training

## Output
Model generates coherent small stories for kids.

## Author
Nishant Singh
