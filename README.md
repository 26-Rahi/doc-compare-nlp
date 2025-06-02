#  NLP Document Comparison App

A Django-based web app to upload two or more documents (PDF, DOCX, PPTX, CSV, XLSX, TXT), summarize them section-by-section using NLP, and compare them semantically.

# Features

-  Upload multiple file types
-  Automatic section-wise summarization (Intro, Methodology, Results, etc.)
-  Semantic comparison using Sentence Transformers
-  Similarity scores for each section
-  Highlights missing or new sections
-  Simple web UI built with Django

# Tech Stack

- Django 4.x
- Transformers (Hugging Face)
- Sentence Transformers
- PyMuPDF, python-docx, python-pptx, pandas
- HTML + CSS
