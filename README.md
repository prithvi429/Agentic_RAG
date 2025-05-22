# Agentic AI

Agentic AI is a demonstration project that combines LangChain, LangGraph, and advanced retrieval-augmented generation (RAG) techniques for building agentic AI workflows with SQL and LLMs.

## Features
- **LangChain & LangGraph Integration**: Build complex, multi-step agent workflows.
- **Retrieval-Augmented Generation (RAG)**: Use Chroma vectorstore and HuggingFace embeddings for semantic search.
- **Web Document Loading**: Load and process web content for knowledge-augmented agents.
- **Customizable Agent States**: TypedDict-based state management for flexible agent design.
- **Graph Visualization**: Visualize your workflow graphically in Jupyter.

## Quick Start
1. **Clone the repository**
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
3. **Set up your environment**
   - Add your API keys (e.g., `GROQ_API_KEY`) to a `.env` file.
4. **Run the notebooks**
   - Open `Agentic_rag.ipynb` or `lang_graph_info.ipynb` in VS Code or Jupyter.

## Example Workflow
- Load web documents
- Split and embed text
- Store in Chroma vectorstore
- Retrieve relevant chunks
- Use an LLM agent to answer questions with context

## Technologies Used
- [LangChain](https://github.com/langchain-ai/langchain)
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [ChromaDB](https://www.trychroma.com/)
- [HuggingFace Embeddings](https://huggingface.co/)
- [Python-dotenv](https://pypi.org/project/python-dotenv/)

## Screenshots
![Workflow Example](docs/workflow_example.png)

## License
MIT License