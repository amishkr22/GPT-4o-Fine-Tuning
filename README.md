# GPT-4o Fine-Tuning for Logical Reasoning
This repository contains a script for fine-tuning the GPT-4o model to enhance its logical reasoning skills. The fine-tuning process leverages a custom dataset and the OpenAI API to improve the model's ability to handle complex logical queries.

## About Dataset
[garage-bAInd/Open-Platypus](https://huggingface.co/datasets/garage-bAInd/Open-Platypus)
This dataset is focused on improving LLM logical reasoning skills and was used to train the Platypus2 models. It is comprised of the following datasets, which were filtered using keyword search and then Sentence Transformers to remove questions with a similarity above 80%:
<div align='centre'>
  <img src="https://github.com/user-attachments/assets/c81d2fd1-d9cd-49fb-a0ed-d14bf884379a" alt="Dataset Image" />
</div>
![image]()


## GPT-4o
<div align='centre'>
  <img src="https://github.com/user-attachments/assets/b6c9776f-ca51-41e2-9300-e4e8f97c0dbc" alt="Dataset Image" />
</div>

GPT-4o is a state-of-the-art generative AI model designed to handle a wide range of text-based tasks with enhanced logical reasoning capabilities. It is a variant of OpenAI's GPT-4, specifically fine-tuned to improve its performance on complex logical queries and structured prompts.
- GPT-4o is available through the OpenAI API, allowing for integration into applications and services via a subscription model.
- Users can fine-tune GPT-4o using custom datasets to align the model's behavior with specific requirements or domains.

Fine-tuning GPT-4o with relevant datasets improves its performance on logical reasoning tasks, making it more effective in scenarios requiring structured responses and accurate reasoning. The model benefits from targeted training that enhances its ability to handle complex queries and provide high-quality responses.
