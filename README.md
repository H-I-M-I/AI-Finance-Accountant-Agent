# AI-Finance-Accountant-Agent

This project implements a **modular AI-powered Finance Research and Analysis System** consisting of **three specialized agents**:
1. **Tool-Calling Web Research Agent**: Fetches real-time financial data from web and news sources.
2. **RAG-Based Query Agent**: Answers finance-related queries by retrieving knowledge from embedded PDFs.
3. **Deep Research Analyst Agent**: Conducts advanced, multi-phase financial investigations with expert-level reporting.

Each agent is designed to autonomously assist in financial services with tasks like:
- Market research
- Trend analysis
- Investment advisory reports
- Corporate financial summaries
- Academic financial studies

## System Architecture

| Agent | Core Capability | Tools & Techniques |
|:-----|:-----------------|:------------------|
| Agent 1 | Web Search Research | DuckDuckGo Search + Newspaper4k |
| Agent 2 | Retrieval-Augmented QA | PDF Parsing + PgVector Embedding + LLM |
| Agent 3 | Deep Financial Analysis | Real-time Search + Critical Analysis + Structured Report Writing |

## Methodology

- **Tool-Augmented Agents**: Combine LLMs with external tools (search engines, scrapers, document parsers).
- **RAG (Retrieval-Augmented Generation)**: Improves factual accuracy by retrieving information from indexed sources.
- **Multi-Phase Research Workflow**: Structured approach to fact-finding, cross-verification, and expert reporting.
- **Embedding Knowledge Bases**: Converts PDFs into searchable vectors for enhanced contextual answering.

## Tools & Technologies

- **LLM Model Provider**: [Groq API](https://groq.com/)
- **Agent Framework**: [Agno](https://www.agno.com/)
- **Web Search & Scraping**: DuckDuckGo Search API + Newspaper4k
- **Vector Database**: [PgVector](https://pypi.org/project/pgvector/)
- **Embeddings**: [Sentence-Transformers](https://huggingface.co/sentence-transformers)
- **PDF Handling**: pypdf
- **Containerization** (Optional, for scalability): Udocker
- **Execution Platform**: Google Colab

## Key Features
✅ Multi-Agent Financial Research  
✅ Real-Time Web Data Integration  
✅ Embedded Knowledge Base Querying  
✅ Fact-Checked, Structured Reporting  
✅ Extendable & Modular Framework

## Future Improvements

- Integrate streaming output with advanced UI (e.g., Streamlit, Gradio).
- Automate selection between agents based on query type.
- Scale to larger document repositories and multi-modal inputs (images, spreadsheets).
