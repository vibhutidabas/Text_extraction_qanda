**Overview**

This project involves extracting hardware product specifications from a GivEnergy data sheet using an open-source Large Language Model (LLM), specifically Ollama. The LLM was run optimally on a single or multi-node cluster to process the PDF and extract relevant data efficiently.

**Requirements**

1. Ollama installed on your system

2. Python (recommended version 3.8 or higher)

3. Necessary libraries: pypdf, ollama, pandas (for structured data storage)

**Installation**

Ensure you have Ollama installed and set up. If not, install it following the official guide:

Install required Python dependencies:

pip install pypdf pandas

**Execution Steps**

1. Load the PDF file: Use pypdf to extract text from the document.

2. Preprocess Text: Clean and structure the extracted content.

3. Run Inference using Ollama: Query the model for extracting structured data.

4. Store Extracted Data: Save the extracted data in a structured format (CSV, JSON, etc.).

5. Q&A on Extracted Data: Use Ollama to answer specific questions about the document.


**Notes**

Ensure the model is optimized for processing PDFs effectively.

If running on a multi-node cluster, distribute inference tasks for improved efficiency.
