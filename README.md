# KNIMEZoBot: Enhancing Literature Review with Zotero and KNIME OpenAI Integration using Retrieval-Augmented Generation

## Description

The "KNIMEZoBot" represents an innovative approach to enhance the efficiency of literature reviews and research by seamlessly integrating Zotero, a widely-adopted reference management tool, with OpenAI's potent natural language processing capabilities. This project's primary goal is to simplify the retrieval of PDFs from Zotero group or user libraries, including the option to filter by collections, and subsequently employ OpenAI within the Konstanz Information Miner (KNIME) workflow to generate insightful questions and extract valuable answers from academic papers. The KNIMEZoBot utilizes a Retrieval-Augmented Generation (RAG) architecture, which combines a vector semantic similarity search to identify relevant passages from the retrieved PDFs with large language models to synthesize natural language responses based on the information extracted from those passages. This allows the KNIMEZoBot to provide informative answers to questions by efficiently searching over academic papers and extracting salient facts and key points.

## Features

- Seamless integration of Zotero and OpenAI within KNIME
- Retrieval of PDFs from Zotero libraries
- Filtering of PDFs by collections
- Generation of insightful questions from academic papers
- Extraction of valuable answers using large language models

## Getting Started

### Prerequisites

Before you begin, ensure you have the following prerequisites:

- **KNIME Analytics Platform (Version 5.1.1)**: Used as the core environment for building data workflows.

- **Python (Version 3.9)**: Integrated into KNIME to leverage Python libraries and machine learning capabilities.

### Installation

To install the necessary Python packages, execute the following commands in the same Python environment used in your KNIME settings:

```bash
pip install pandas
pip install openai
pip install langchain
pip install unstructured
pip install fitz
pip install PyPDF2
pip install PyMuPDF
pip install "unstructured[pdf]"
