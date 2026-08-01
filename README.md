# Financial Research Agent

An agentic AI system that autonomously researches any NSE-listed company 
and generates a structured one-page PDF research report.

## What it does
- Fetches latest news via Tavily
- Pulls NSE price data and moving averages via yfinance
- RAG over earnings call transcripts via ChromaDB
- Generates a structured PDF report

## Tech Stack
- LangGraph (agent orchestration)
- LangChain + ChromaDB (RAG pipeline)
- yfinance (market data)
- Tavily API (news)
- FastAPI (backend)
- Streamlit (frontend)
- ReportLab (PDF generation)

## Status
🚧 In progress
