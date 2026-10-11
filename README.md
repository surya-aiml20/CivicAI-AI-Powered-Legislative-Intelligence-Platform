# CivicAI

Legislative Watchdog is an AI-powered UK bills intelligence platform that helps users search, analyze, and understand parliamentary bills in plain English. The platform aggregates UK bill data, extracts textual content from PDFs, summarizes legislation, classifies relevant industries, and allows users to ask questions using retrieval-augmented generation (RAG).

This project is designed to make legislative information more accessible to businesses, researchers, and policy analysts.

## Features

- Browse UK parliamentary bills
- Search bills by keyword and topic
- Filter bills by industry
- View structured summaries of each bill
- Extract and process text from public bill PDFs
- Generate key change and compliance insights
- Ask natural-language questions about a bill
- Store and query bill metadata in Supabase
- Automate ingestion and processing using Airflow

## Tech Stack

- Python
- Streamlit
- Supabase
- Groq LLM API
- Airflow
- pdfplumber
- Python-dotenv

## How It Works

UK Parliament bill metadata is fetched from the official API.
Public bill PDFs are downloaded and stored.
PDF text is extracted using pdfplumber.
Groq-based LLMs generate summaries and industry tags.
Streamlit provides the interactive interface.
Users can search and ask questions about bills in natural language.
Supabase stores the structured bill information.

## Prerequisites
Before running the project, ensure you have:
Python 3.10+
A Groq API key
A Supabase project and service role key
Access to a valid Groq model

## Demo

![Legislative Watchdog Demo](./demo/Screenshot%202026-10-12%20021136.png)
