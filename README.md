# Case-Based Reasoning (CBR) System for Surat Pemalsuan Detection

This repository implements a Case-Based Reasoning (CBR) system to analyze and detect document forgery (Pemalsuan Surat) using Python 3.11.

## Project Structure

```text
├── data/
│   ├── raw_pdf/      # Original PDF documents
│   ├── raw_text/     # Extracted text files
│   └── processed/    # Processed cases / structured database (JSON/CSV)
├── eval/             # Evaluation scripts and metrics
├── models/           # Retrieval, similarity, and adaptation models/modules
├── notebooks/        # Jupyter notebooks for exploration and experimentation
├── results/          # Output results and reports
├── scripts/          # Command-line helper scripts
├── requirements.txt  # Project dependencies
└── README.md         # Project documentation
```

## Setup & Installation

1. Create a virtual environment using Python 3.11:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
