---
base_model: TinyLlama/TinyLlama-1.1B-Chat-v0.1
library_name: peft
---

# Model Card for Model ID

This is a fine-tuned version of the Tiny Llama Chat model, used to act as a recipe generator.


## Model Details

### Model Description
This model is a fine-tuned variant of the Tiny Llama Chat, specifically designed to function as a recipe generator. It leverages the compact and efficient architecture of Tiny Llama while being tailored to understand and produce detailed culinary recipes, offering users a robust tool for creating and exploring various dishes. It was fine-tuned on this [dataset](https://huggingface.co/datasets/TigerResearch/tigerbot-kaggle-recipes-en-2k).


### Model Sources [optional]

<!-- Provide the basic links for the model. -->

- **HuggingFace Repository :** [Link](https://huggingface.co/AshArya/tinyLlama-recipes)
- **Base Model :** [Link](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v0.1)

## Uses

<!-- Address questions around how the model is intended to be used, including the foreseeable users of the model and those affected by the model. -->

Can be used to generate recipes.


### Framework versions


- PEFT 0.6.2
