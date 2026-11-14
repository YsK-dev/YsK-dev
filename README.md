# Yusuf Sertkaya

**AI Engineer · LLM, RAG, fine-tuning · Python back end and full-stack**

I build practical AI systems in Python, from the model to a tested web application: question answering over documents with retrieval-augmented generation (RAG), multi-agent assistants, and small language models fine-tuned for a single task. I measure what I build against simple baselines. I also work on Turkish-language NLP.

[Website](https://ysk-dev.github.io) · [LinkedIn](https://www.linkedin.com/in/yusuf-sertkaya-87888a244/) · [Hugging Face](https://huggingface.co/YsK-dev) · [Kaggle](https://www.kaggle.com/yusufsertkayaysk) · [Email](mailto:yusufsertkayaysk@gmail.com)

## Selected projects

| Project | What it does | Built with |
| :--- | :--- | :--- |
| [Local RAG Q&A](https://github.com/YsK-dev/Rag-case-study-) | Ask questions about your own documents, fully on your machine. Hybrid search (semantic + BM25) and streamed answers with sources, evaluated with an LLM judge. | FastAPI, Ollama, ChromaDB |
| [Multi-agent assistant](https://github.com/YsK-dev/AgentsCase) | A supervisor agent sends each question to the agents it needs: researcher, analyst, editor. Web search, restricted Python execution and unit tests. | LangGraph, Ollama, SearXNG |
| [Zima](https://github.com/YsK-dev/zima) | Health-advice assistant for people over 70. Synthetic dataset generation and LoRA fine-tuning of Qwen2.5-1.5B. | Unsloth, Transformers, Gradio |
| [Finance sentiment](https://github.com/YsK-dev/finance-sentiment-app) | Labels a stock's news headlines with FinBERT, and measures it: on 2,388 labelled headlines FinBERT reaches macro F1 0.668, a simple model trained on the same kind of text 0.761. Tests, CI, one Docker image. | FastAPI, React, Docker |
| [Datathon 2025](https://github.com/YsK-dev/datahon25) | Predicts how much each e-commerce session is worth from user events. | pandas, CatBoost |
| [ALS recommender](https://github.com/YsK-dev/Bigdata-ALS-Pyspark) | Movie recommendations with collaborative filtering on Spark. | PySpark |

## Models on Hugging Face

- [TurkWeb-Edu Classifier](https://huggingface.co/YsK-dev/TurkWeb-Edu-Classifier-V5) scores the educational quality (0–5) of Turkish web text. It is a Turkish counterpart of the FineWeb-Edu classifier.
- [TurkWeb-Edu Student](https://huggingface.co/YsK-dev/TurkWeb-Edu-Student-Qwen1.5B-SOTA) is a 1.5B Qwen model that writes its reasoning in Turkish before it gives the score.
- [Zima](https://huggingface.co/YsK-dev/zima-qwen-geriatric-1.5b) and its [training dataset](https://huggingface.co/datasets/YsK-dev/geriatric-health-advice).

## Tools I use

Python · PyTorch · Hugging Face Transformers · LangChain / LangGraph · Ollama · FastAPI · React · ChromaDB · scikit-learn · PySpark · Docker · GitHub Actions · AWS
