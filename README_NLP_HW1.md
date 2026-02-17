# NLP_HW1
Genre Analysis: Slave Narratives vs. Romance Novels
Exploring LLR, LDA, Model Tuning, Topic Collapse.

#Project Overview
This project uses Natural Language Processing (NLP) to analyze and differentiate between two distinct literary genres from the 19th century. The goal was to test LDA, LLR can isolate thematic elements despite shared historical vocabulary.

#The Corpus
The dataset consists of a 6-novel corpus retrieved from Project Gutenberg:
   #Category Slave:  The Garies and Their Friends, 1857, 36 chapters, Uncle Tom's Cabin, 1852, 43 chapters, Clotelle, 1867, 28 chapters
   #Category Romance: Emma, 1815, 55 chapters, The Age of Innocence, 1920, 34 Chapters,  Wuthering Heights, 1847, 34 Chapters

#Tools & Libraries
This analysis was performed using Python google colab and the following libraries:
Scikit-Learn: For LDA modeling and TF-IDF Vectorization.
Pandas & NumPy: For data manipulation and matrix management.
NLTK: For stop-word removal.

#Setup and Execution
Prerequisites
Ensure you have Python. You can install the required dependencies using pip:

#How to Run
Open the Notebook: Launch Jupyter Lab or Notebook and open analysis_notebook.ipynb.
Execute Cells: Run the cells in order. The notebook is designed to fetch text directly from Project Gutenberg URLs; no local text files are required to begin the analysis.
