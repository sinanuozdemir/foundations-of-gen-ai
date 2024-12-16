![oreilly-logo](images/oreilly.png)

# Transformer Architectures for Generative AI

This repository contains code for the [O'Reilly Live Online Training for "Transformer Architectures for Generative AI"](https://learning.oreilly.com/live-events/transformer-architectures-for-generative-ai/0642572010589)

This course is designed to provide a deep understanding of transformer architectures and their revolutionary impact on both natural language processing (NLP) and vision tasks. This course is crucial for professionals looking to stay at the forefront of AI advancements, as transformers are now the cornerstone of many state-of-the-art models. By combining theory with practical exercises, participants will learn how to harness the power of transformers to tackle complex problems in text, image, and multimodal AI.

## Notebooks

### Introduction to LLMs

1. BERT - the beginnings of LLMs
	- [Introduction to BERT](notebooks/intro_to_bert.ipynb)
	- [Classification with BERT vs ChatGPT](notebooks/BERT%20vs%20GPT%20for%20CLF.ipynb)
		- [Open in Colab](https://colab.research.google.com/drive/1elfu-6gaj0KWtIQMyeHYWqqkNUgA6hFn?usp=sharing)
2. T5 - the beginnings of instructional alignment
	- [Off the shelf NLP with T5](notebooks/t5.ipynb)
3. GPT - How LLMs learned to talk
	- [Introduction to GPT](notebooks/intro_to_gpt.ipynb)
4. Multimodal LLMs
	- [Image Captioning with Vision Transformers](notebooks/image_captioning_vision_transformer.ipynb)
		- [Open in Colab](https://colab.research.google.com/drive/1OQlX_cD4mVo8vB3A4co1JIfl9Vt7rhzN?usp=sharing)
5. [Inspecting LLM token embeddings](notebooks/LLM Embeddings.ipynb) - Explore how different attention mechanisms lead to different token embeddings

### Advanced LLMs

**LLM Classification**

  - [`bert_app_review.ipynb`](notebooks/bert_app_review.ipynb): Fine-tuning a BERT model for app review classification.
  - [`openai_app_review_fine_tuning.ipynb`](notebooks/openai_app_review_fine_tuning.ipynb): Fine-tuning OpenAI models for app review classification.

**Visual Q/A**

  - [`constructing_a_vqa_system.ipynb`](notebooks/constructing_a_vqa_system.ipynb): Step-by-step guide to constructing a Visual Question Answering (VQA) system using GPT-2 and Vision Transformer.
	- [`using_our_vqa.ipynb`](notebooks/using_our_vqa.ipynb): Using the VQA system built in the previous notebook.


**SAWYER - Instructional Fine-tuning**

  - [`SAWYER_LLAMA_SFT.ipynb`](notebooks/SAWYER_LLAMA_SFT.ipynb): Fine-tuning the Llama-3 model to create the SAWYER bot.
  - [`SAWYER_Reward_Model.ipynb`](notebooks/SAWYER_Reward_Model.ipynb): Training a reward model from human preferences for the SAWYER bot.
  - [`SAWYER_RLF.ipynb`](notebooks/SAWYER_RLF.ipynb): Applying Reinforcement Learning from Human Feedback (RLHF) to align the SAWYER bot.
  - [`SAWYER_USE_SAWYER.ipynb`](notebooks/SAWYER_USE_SAWYER.ipynb): Using the SAWYER bot.

**Distillation**

- [Go Emotion Distillation](notebooks/go_emotion_distillation.ipynb): Exploring knowledge distillation techniques for transformer models.


**Agents / RAG**

- [RAG Retrieval](notebooks/RAG_Retrieval.ipynb): An introduction to vector databases, embeddings, and retrieval

		
**Probing**

- [Probing Chess Playing LLMs](https://colab.research.google.com/drive/114turFLNxLJXiIseDWl1BDJmont0VD8h?usp=sharing)

- There are over a dozen notebooks for the birth year/death year probing example so I will only share a few key ones here:
	  - [Llama-3 8B Instruct with prompt "Who is {NAME}"](https://colab.research.google.com/drive/1e1d9fATVjVun-_tPj4vS_DSTGaIfxs01?usp=sharing)
	  - [BERT-large-cased no prompt](https://colab.research.google.com/drive/1cizgoh1J6Y-DHBrOkNTFo9Y1CypjwuQM?usp=sharing)
	  - [Mistral-7B-Instruct-v0.3 with prompt "Who is {NAME}"](https://colab.research.google.com/drive/1VL3betxqVZ_H3_8XmLbjE0hEjaoy-HPV?usp=sharing)


- [Evaluating Tool Selection](notebooks/agent_positional_bias_tools.ipynb) - Calculating the accuracy of tool selection between different LLMs and quantifying the positional bias present in auto-regressive LLMs

## Instructor

**Sinan Ozdemir** is founder and CTO of LoopGenius, where he uses state-of-the-art AI to help people create and run their businesses. He has lectured in data science at Johns Hopkins University and authored multiple books, videos and numerous online courses on data science, machine learning, and generative AI. He also founded the recently acquired Kylie.ai, an enterprise-grade conversational AI platform with RPA capabilities. Sinan most recently published Quick Guide to Large Language Models, and launched a podcast audio series, AI Unveiled. Ozdemir holds a master’s degree in pure mathematics from Johns Hopkins University.
