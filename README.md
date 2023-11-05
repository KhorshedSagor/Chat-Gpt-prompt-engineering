# Chat-Gpt-prompt-engineering
Best practices for  prompt engineering using OpenAI API

# Find the best model that fits your purpose:
1. For normal reasoning tasks that don't require multiple thinking steps can be served using GPT-3.5 models
2. For complex tasks always use GPT-4 models

# Try to eliminate hallucinations as much as possible through prompt


# To solve complex problems using GPT-4
1. Few shot approach --> Best for classification problems
2. Setting up a persona --> Specifically for solving complex problems through system message

# For fixed JSON output using GPT-4
1. Use function call schema in the prompt


# If any of the above methods fails to solve your problems using the pre-trained models then fine-tuning is the ultimate way to go.

# But with fine-tuning we have a few problems
# One of the main problems is catastrophic forgetting.
# Easiest way is instruction_fine_tuning


# RLHF
