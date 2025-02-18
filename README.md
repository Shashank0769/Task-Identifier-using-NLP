# Task Identifier using NLP  

This project extracts and categorizes tasks from unstructured text using a heuristic-based approach (without LLMs). It identifies:  
✅ **Tasks** (based on action words)  
✅ **Responsible Person** (using named entities and context)  
✅ **Deadlines** (extracting date/time references)  
✅ **Categories** (Shopping, Cleaning, etc.)  

## Features  
- **Preprocessing:** Tokenizes text into sentences.  
- **Task Extraction:** Identifies actionable statements.  
- **Entity Recognition:** Finds the person responsible.  
- **Deadline Detection:** Extracts due dates if mentioned.  
- **Task Categorization:** Groups tasks into predefined categories.  
- **CSV Export:** Saves structured output.  

## Installation  
```bash
pip install spacy nltk pandas
python -m spacy download en_core_web_sm
