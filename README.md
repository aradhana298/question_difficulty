# question_difficulty
# question_difficulty Dataset

## Description
This repository contains the dataset titled "question_difficulty", which includes 9,041 entries. The dataset comprises questions categorized by their difficulty levels: Simple, Average, and Tough. Each entry contains a question (title) and its corresponding difficulty level.

### Distribution of Difficulty Levels
- **Simple (3,195 entries)**: These questions are straightforward, generally requiring basic knowledge or one-line responses. For example, "Where is the Red Fort located in India?" pertains to simple general knowledge.
- **Average (3,546 entries)**: This category includes moderately challenging questions that demand some analytical thinking or a deeper understanding of the subject matter. These questions bridge the gap between simple queries and complex problem-solving. For example, "How can I change the attribute value of an HTML tag?"
- **Tough (2,951 entries)**: Questions in this category involve complex calculations, utilize scientific terminology, or require advanced problem-solving skills. Typically sourced from specialized academic or professional examinations, these questions are intended to challenge the respondent significantly. For example, "Prove that the graph with adjacency matrix [[0 1 0 0] [1 0 1 1] [0 1 0 1] [0 1 1 0]] is bipartite."

### Sources of Questions
The dataset comprises questions sourced from a variety of domains to ensure a broad spectrum of complexity and applicability. It includes technical questions from platforms like Stack Overflow, academic challenges from GATE exams and engineering course materials, general knowledge queries, and complex mathematics problems. This diversity enhances the dataset's robustness, enabling the effective training and evaluation of machine learning models across different levels of question difficulty.

## Contents
The repository contains the following files:
- `question_difficulty.csv`: The primary dataset file in CSV format.
- `README.md`: This file, providing an overview of the dataset and repository contents.

## Data Fields
The dataset includes the following fields:
- `Title`: The question itself.
- `Difficulty`: The difficulty level of the question, which can be "Simple", "Average", or "Tough".

## Usage
To use this dataset, you can clone the repository and read the CSV file using your preferred data analysis tools. Below is a simple example using Python and pandas:

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('path/to/question_difficulty.csv')

# Display the first few rows of the dataset
print(df.head())
