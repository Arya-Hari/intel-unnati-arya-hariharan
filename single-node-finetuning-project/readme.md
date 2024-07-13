# Recipe Generation Chatbot

This folder contains the notebooks used for fine-tuning the Tiny Llama Chat (Version 0.1) to act as a recipe chatbot.
* The model was finetuned on a dataset downloaded from HuggingFace, which is in the same format of the Alpaca dataset.
* The model, after fine-tuning, was pushed onto HuggingFace Hub for easy use.
* The model was loaded using Tranformers methods in the [inference-jupyter-notebook](https://github.com/Arya-Hari/intel-unnati-arya-hariharan/blob/main/single-node-finetuning-project/inference-jupyter-notebook.ipynb) and was tested against custom input.
* The training and evaluation results, along with the adapter model files, are present in the "output" folder.

<b> Note : The model was finetuned using LoRA </b>
