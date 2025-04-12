# GenAI Notebooks Collection

A collection of Jupyter notebooks demonstrating various Generative AI techniques and implementations.

### Course Materials
- [PPT Presentation](https://docs.google.com/presentation/d/1JbUhN2pc7OQDxGSXe8ewXgIlQ8cvYmY0LVkrMP8-vgA/edit?usp=sharing)
- [Course Repository](https://tinyurl.com/ASgenai)
- Supporting Documents:
  - `Harnessing Generative AI (3).pdf`
  - `mcp_gen_ai_slides.pdf`
  - `reasoning_gen_ai_slides.pdf`

## Notebooks

### LLM Fundamentals
- [1_How_LLM_works.ipynb](1_How_LLM_works.ipynb) - Introduction to LLM concepts
- [2_Learn_Prompting.ipynb](2_Learn_Prompting.ipynb) - Learn prompting techniques

### RAG (Retrieval Augmented Generation)
- [3_Simple_RAG.ipynb](3_Simple_RAG.ipynb) - Basic implementation of RAG
- [4_RAG_with_Gemma,_Langchain_and_HuggingFace.ipynb](4_RAG_with_Gemma,_Langchain_and_HuggingFace.ipynb) - Advanced RAG implementation using:
  - Gemma LLM
  - LangChain 
  - HuggingFace tools
  - ChromaDB for vector storage
  - SentenceTransformers for embeddings

### Agents and Advanced Topics
- [5_Building_an_agent_with_LangGraph.ipynb](5_Building_an_agent_with_LangGraph.ipynb) - Demonstrates building a stateful graph-based application (BaristaBot)
- [6_Agentic_AI_Huggingface.ipynb](6_Agentic_AI_Huggingface.ipynb) - Advanced agent implementations using HuggingFace

## Important Resources

### Technical Resources
- [Transformer Visualization](https://bbycroft.net/llm)
- [Illustrated Transformer Blog](https://jalammar.github.io/illustrated-transformer/)
- [Google Gemini API Portal](https://aistudio.google.com/app/apikey)
- [ChromaDB Documentation](https://www.trychroma.com/)
- [LlamaIndex Documentation](https://docs.llamaindex.ai/en/stable/)
- [Ollama - Run models locally](https://ollama.com/)
- [Gemma Model on HuggingFace](https://huggingface.co/google/gemma-3-1b-it)

### Additional Learning
- [DeepLearning.AI Courses](https://www.deeplearning.ai/courses/)
- [Andrew Ng Courses](https://www.andrewng.org/courses/)
- [Andrej Karpathy's Transformer Videos](https://www.youtube.com/@AndrejKarpathy/videos)

## Key Technologies

- LangChain
- LangGraph
- Gemma/Gemini
- HuggingFace
- ChromaDB
- SentenceTransformers
- PyPDF for document loading

## Getting Started

1. Install required dependencies:
```sh
pip install langchain chromadb sentence-transformers langgraph langchain-google-genai
```

2. Set up necessary API keys (refer to [imps_links](imps_links) for links)

3. Start with the fundamentals notebooks before moving to advanced topics

## Support

For any questions or clarifications, contact: ntech0709@gmail.com