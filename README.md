# GPT-XAI
A story generation model for model prediction explanation.

## Outline
- GPT-XAI class for general use
    - Takes model output and example prompts
    - Returns either a fine-tuned GPT model, a few-shot seeding prompt to use, or an API endpoint to use.
- RTA
    - A specific instance of GPT-XAI for the RTA prediction model