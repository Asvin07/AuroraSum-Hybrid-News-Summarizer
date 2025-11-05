# AuroraSum-Hybrid-News-Summarizer
AuroraSum is a modular, research-oriented news/document summarization toolkit that blends neural and extractive summarization. The project features Jupyter notebooks for direct experimentation, quick prototyping with Gradio UI, and extensibility for advanced research use or integration.

Features
Hybrid Summarization: Combines transformer-based abstractive (e.g., BART) and extractive (TextRank) approaches for clean, high-quality summaries.

Interactive Demos: Use in Colab for iterative development and testing.

API & Web UI Ready: Notebooks include draft code for FastAPI REST and Gradio-driven browser demos.

Auto Evaluation: Built-in ROUGE, METEOR, and BERTScore for scientific comparison.

Hyperparameter Optimization: Automated search with Optuna.

Clean Design: Modular code for easy customization, extension, and dataset/model swapping.

Notebooks
AuroraSum_(2) (1).ipynb: Full pipeline with modular code blocks for data prep, hybrid summarizer logic, evaluation, optimization, and deployment code templates.

Aurora_Sum_Basic_UI-2.ipynb: A Lightweight notebook with a simple Gradio user interface for fast summarization tests.

Limitations & RAG/FAISS Attempt
During development, I experimented with integrating FAISS for vector search and Retrieval-Augmented Generation (RAG) methods. However, both approaches proved to be computationally intensive, making full deployment infeasible within the intended environment and compute budget. Potential future work may revisit lighter-weight variants or optimized pipelines to bring these functionalities into production.

Citation & Credits
Leverages open-source libraries: HuggingFace Transformers/Datasets, Sumy, Evaluate, NLTK, Gradio, Optuna.

Foundations: BART (Lewis et al., 2019), TextRank (Mihalcea & Tarau, 2004).
