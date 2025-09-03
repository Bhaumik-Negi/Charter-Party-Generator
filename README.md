# Document Processing and Merging System

## Description
Automates the extraction, merging, and tracking of contract documents (e.g., maritime charter parties), producing professional PDF/DOCX outputs.

## Technologies
Python, Flask, python-docx, PyPDF2, reportlab, regex

## Features
- Upload base CP (DOCX) and recap (PDF/DOCX) documents
- Extracts key data using regex and merges into templates
- Tracks changes (additions, deletions, modifications) with logs
- Generates DOCX and PDF outputs reflecting merged data
- Web interface for easy file uploads and downloads

## Setup
1. Install Python 3.x
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `python app.py`
4. Open browser at http://127.0.0.1:5000 and upload sample files

## Sample Data
- `base_cp.docx` – Charter party template
- `recap_doc.pdf` – Recap document with updated contract info
