# Mastering the AI Toolkit 🛠️🧠

## Overview
This repository contains the group assignment for **AI Tools and Applications** under the theme *"Mastering the AI Toolkit"*.  
The project demonstrates theoretical understanding, practical implementation, and ethical reflection using modern AI frameworks.

---

## Repository Structure
ai-tools-assignment/
  code/
    irisdecisiontree.ipynb
    mnist_cnn.ipynb
    spacy_nlp.ipynb
  report/
    AIToolsAssignment.pdf
  README.md

---

## Tools & Frameworks
- **Scikit-learn** → Classical machine learning (Iris dataset, decision tree classifier)  
- **TensorFlow** → Deep learning (MNIST CNN classifier)  
- **spaCy** → Natural Language Processing (NER on Amazon reviews)  
- **TextBlob** → Rule-based sentiment analysis  
- **Google Colab** → Development environment with free GPU  

---

## How to Run
1. Open any notebook in the `code/` folder.  
2. Run in **Google Colab** (recommended).  
3. Install dependencies if needed:
   ```bash
   pip install tensorflow scikit-learn spacy textblob matplotlib pandas
   python -m spacy download en_core_web_sm
