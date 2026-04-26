# 📚 Automated Book Summarizer Agent
An end-to-end NLP pipeline built to condense long-form content (books, journals, reports) into concise summaries using **Transformers**.

## 🚀 Key Features
- **Recursive Chunking:** Successfully processes texts that exceed model token limits (like full books).
- **Transformer Architecture:** Leverages pre-trained LLMs via Hugging Face for high-quality abstractive summarization.
- **Automated Workflow:** An agent-like approach to processing multiple text segments and merging them into a coherent final summary.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Hugging Face Transformers, PyTorch, Tokenizers
- **Models:** BART / T5 (or whichever model you used)

## 📖 Usage
1. Upload your long-form text or book file.
2. The agent splits the text into manageable chunks.
3. Each chunk is summarized and then synthesized into a **Final Summary**.

hello
