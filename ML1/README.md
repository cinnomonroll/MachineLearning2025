# Retrieval-Augmented Generation with Agents

This project implements a Retrieval-Augmented Generation (RAG) pipeline using large language models (LLMs) and a modular, agent-based design. The system combines powerful LLM inference with web-based retrieval tools, orchestrated by specialized agents for flexible and up-to-date question answering.

---

## Architecture

This project follows a **RAG with Agents** flow, illustrated below:

<p align="center">
  <img src="ML1/images/Screenshot 2025-07-06 at 2.19.23 PM.png" alt="RAG with Agents Architecture" width="600"/>
</p>

The pipeline includes:
- **Keyword Extraction Agent:** Extracts search keywords from user questions.
- **Search Tool:** Retrieves relevant web information using the extracted keywords.
- **Question Extraction Agent:** Reformulates or clarifies the question if needed.
- **QA Agent:** Synthesizes the final answer using retrieved results and clarifications.

> **Note:**  
> My implementation closely follows this agent-based RAG architecture.

---

## Environment Setup

- Python 3.8+ required
- Major dependencies: PyTorch, Hugging Face Transformers, etc.
- All dependencies and setup steps are provided in the notebook.

> **Note:**  
> The quantized LLaMA 3.1 8B model (~8GB) will be downloaded as part of the setup.

---

## Usage

1. **Clone the repository**
    ```bash
    git clone https://github.com/yourusername/retrieval-augmented-generation-agents.git
    cd retrieval-augmented-generation-agents
    ```

2. **Open the Jupyter Notebook**
    ```bash
    jupyter notebook ml2025-homework-1.ipynb
    ```

3. **Follow the notebook instructions**  
   - Install dependencies  
   - Download the model and dataset  
   - Run the cells step by step

---

## Results

- Integrates LLM inference with real-time web retrieval
- Modular agent system for multi-step, multi-source reasoning

---

## References

- [LLaMA 3.1 8B model](https://github.com/meta-llama/llama)
- [HUNG-YI LEE Machine Learning 2025](https://speech.ee.ntu.edu.tw/~hylee/ml/2025-spring.php)


