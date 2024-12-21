# Weekly AI Agents report
December 30, 2024

## Tools
- [**Open Canvas**](https://github.com/langchain-ai/open-canvas?tab=readme-ov-file) is an open source web application for collaborating with agents to better write documents. It is inspired by OpenAI's "Canvas", but with a few key differences.
- [**Google: gemini 2.0 flash thinking**](https://huggingface.co/spaces/akhaliq/anychat) on Hugging Face Anychat. 
- [**Jupyter Agent**](https://huggingface.co/spaces/data-agents/jupyter-agent) on Hugging Face Spaces.


## Tutorials
- [**Building an LLM Agent to Find Relevant Research Papers from Arxiv**](https://github.com/mistralai/cookbook/blob/main/third_party/LlamaIndex/llamaindex_arxiv_agentic_rag.ipynb) demonstrates how to implement an agentic retrieval-augmented generation (RAG) system using LlamaIndex. This system enables dynamic retrieval of relevant information from the arXiv dataset to enhance the generation capabilities of language models. By integrating LlamaIndex with the arXiv dataset, the notebook showcases the process of building a more intelligent and context-aware AI application.
-[**GenerativeAI Generative AI for Everyone**](https://www.coursera.org/learn/generative-ai-for-everyone?utm_campaign=coursera-campaign-social&utm_medium=institutions&utm_source=deeplearning-ai) is a beginner-level course taught by AI pioneer Andrew Ng, designed to demystify generative artificial intelligence and its applications. The course covers how generative AI works, its common use cases, and guides learners through the lifecycle of a generative AI project, including effective prompt engineering. With approximately 5 hours of content, it aims to empower individuals and businesses to harness AI’s potential responsibly and effectively. 

## Events
- [**OpenAI's "12 Days of OpenAI"**](https://openai.com/12-days/) event, which began on December 5, 2024, features daily announcements of new features, products, and demos. On the last, 12-th day, new reasoning o3 model was introduced.
![alt text](image.png)

## Conversations
- [**Building Anthropic | A conversation with our co-founders**](https://www.youtube.com/watch?v=om2lIWXLLN4) a discussion of shared journey in advancing safe and responsible AI. They discuss the challenges of scaling AI while addressing safety concerns, the origins and impact of initiatives like the Responsible Scaling Policy, and their collaborative culture focused on unity, pragmatism, and mission alignment. Their vision emphasizes using AI to address global challenges, enhance safety, and drive a positive societal impact through innovation and responsibility.


## Papers
- [**A Survey on LLM Inference-Time Self-Improvement**](https://arxiv.org/pdf/2412.14352) by Xiangjue Dong, Maria Teleki, and James Caverlee provides a comprehensive review of techniques that enhance large language models (LLMs) during inference without altering their parameters or requiring additional training.  The authors categorize these methods into three main approaches: independent self-improvement, context-aware self-improvement, and model-aided self-improvement. 
- [**Qwen2.5 Technical Report**](https://arxiv.org/pdf/2412.15115) introduces Qwen2.5, a series of large language models developed by the Qwen Team. These models have been enhanced through extensive pre-training on 18 trillion tokens and refined post-training, including supervised fine-tuning and reinforcement learning, to improve capabilities in reasoning, mathematics, coding, and human preference alignment. The Qwen2.5 series offers models in various sizes, from 0.5B to 72B parameters, with open-weight versions available for public access, and demonstrates competitive performance against state-of-the-art models like Llama-3-405B-Instruct.
- [**OpenAI deliberative alignment: reasoning enables safer language models**](https://openai.com/index/deliberative-alignment/) a training method that teaches language models explicit safety specifications and trains them to reason through these guidelines before responding. This approach enables models to reflect on user prompts, identify relevant safety policies, and generate safer outputs, enhancing adherence to safety standards. Models trained with deliberative alignment, such as OpenAI’s o-series, have demonstrated superior performance on various safety benchmarks compared to previous models.