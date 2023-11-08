**LeetCode Search Engine**

**Overview**

The project is a LeetCode Search Engine that facilitates efficient question retrieval. It employs web scraping, natural language processing, and Flask to offer a user-friendly way to search and find relevant LeetCode questions.

It works in the following manner:

**Data Collection and Validation**
- It uses Selenium web scraping to collect detailed question information from LeetCode, including titles and descriptions.
- Python scripts validate and filter the collected links to ensure accuracy.

**TF-IDF Calculations**
- The engine computes TF-IDF values for each term in the dataset. TF-IDF measures term importance within a document collection.
- This process generates data files, such as inverted index files, a vocabulary file, and IDF value files for each term.

**Backend Infrastructure**
- The backend is developed using Flask, a Python web framework. It handles user input, processes queries, and retrieves the most relevant questions from the dataset.

**Query Processing and Display**
- When a user submits a search query, the engine compares it to the TF-IDF data, calculating question relevance.
- The most relevant questions are displayed as search results, allowing users to find matching questions easily.

 
