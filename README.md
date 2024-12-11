# NLP Project

This project explores Natural Language Processing (NLP) techniques using tools like NLTK and spaCy. It includes tutorials, practical examples, and a workflow for categorizing news articles.

## Features
- **Text Processing with NLTK**: Tutorial on fundamental NLP operations.
- **Word Similarity Analysis with spaCy**: Explore semantic similarities between words.
- **News Categorization**: End-to-end implementation for classifying news articles.
- Includes preprocessed dataset for experimentation.

## Repository Structure
```
NLP/
|-- .gitignore             # Files and directories ignored by Git
|-- pyproject.toml         # Poetry configuration file
|-- poetry.lock            # Locked dependencies
|-- README.md              # Project documentation
|-- notebooks/             # Jupyter notebooks for tutorials and experiments
    |-- nltk_text_tutorial.ipynb
    |-- spacy_word_simalrities.ipynb
    |-- Categorize_news_articles.ipynb
    |-- 20news-bydate_py3.pkz
```

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- Poetry package manager

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd NLP
   ```
2. Install dependencies:
   ```bash
   poetry install
   ```



## Usage

### Running Jupyter Notebooks
1. Start the Jupyter Notebook server:
   ```bash
   poetry run jupyter notebook
   ```
2. Open any of the notebooks in the `notebooks/` directory to explore:
   - **`nltk_text_tutorial.ipynb`**: Learn text processing techniques.
   - **`spacy_word_simalrities.ipynb`**: Analyze word similarities.
   - **`Categorize_news_articles.ipynb`**: Classify news articles using machine learning.

### Dataset
The `20news-bydate_py3.pkz` file contains a preprocessed dataset used in the news categorization notebook.


For any questions or feedback, please feel free to reach out!