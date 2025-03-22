# Cohort Lens
Agentic AI app that leverages **GraphRAG, NVIDIA cuGraph, LangChain, and ArangoDB** to optimize clinical and public health study recruitment. By analyzing medical knowledge graphs, it uncovers hidden connections between patients, conditions, and treatments, enabling smarter cohort selection.

![demo thumbnail](https://github.com/daphinie/cohort_lens/blob/main/cohort_lens_thumbnail.png)

## Built for
[Building the Next-Gen Agentic App with GraphRAG & NVIDIA cuGraph](https://arangodbhackathon.devpost.com/)

## Features
- **GraphRAG-powered AI Agent** for intelligent participant selection.
- **LangGraph & LangChain integration** for multi-step reasoning in study recruitment.
- **NVIDIA cuGraph acceleration** for efficient graph analytics.
- **Medical knowledge graph** built in **ArangoDB** for scalable data relationships.
- **Full-text search with ArangoSearch** for rapid patient and condition lookup.

## Built with
- [LangChain](https://www.langchain.com/), [LangGraph](https://www.langchain.com/langgraph)  
- [NetworkX & NVIDIA cuGraph](https://docs.rapids.ai/api/cugraph/nightly/nx_cugraph/nx_cugraph/)
- [ArangoDB](https://arangodb.com/)  
- [OpenAI API](https://platform.openai.com/docs/overview)
- [Gradio](https://www.gradio.app/)

## Getting started
```bash
# Clone the repository
git clone https://github.com/daphinie/cohort-lens.git
cd cohort-lens

# Set up ArangoDB account

# Run the notebook in Colab with the following variables:
DB_HOST=
DB_PASS=
OPENAI_API_KEY=
```