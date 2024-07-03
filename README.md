# RAG Evaluator

## Overview

RAG Evaluator is a Python library for evaluating Retrieval-Augmented Generation (RAG) systems. It provides various metrics to evaluate the quality of generated text against reference text.

How to build a Retrieval-Augmented Generation (RAG) Evaluation Tool and Python Library! In this video, I will guide you through the process of creating a comprehensive evaluation tool for RAG systems, complete with various metrics to assess the quality of generated text.

✅ Setting up the project structure

✅ Implementing evaluation metrics such as BLEU, ROUGE, BERT Score, Perplexity, Diversity, and Racial Bias
 
✅ Creating a Python library that can be easily installed and used

✅ Writing test cases to ensure the robustness of the tool 
 
✅ Packaging and publishing the library to PyP, you'll have a powerful evaluation tool to enhance the performance and reliability of your RAG systems.

## Installation

You can install the library using pip:

```bash
pip install rag-evaluator
```

## Usage

Here's how to use the RAG Evaluator library:

```python
from rag_evaluator import RAGEvaluator

# Initialize the evaluator
evaluator = RAGEvaluator()

# Input data
question = "What are the causes of climate change?"
response = "Climate change is caused by human activities."
reference = "Human activities such as burning fossil fuels cause climate change."

# Evaluate the response
metrics = evaluator.evaluate_all(question, response, reference)

# Print the results
print(metrics)
```

## Streamlit Web App

To run the web app:

- cd into streamlit app folder.
- Create a virtual env
- Activate
- Install all dependencies
- and run
```
streamlit run app.py
```

## Metrics

The following metrics are provided by the library:

- **BLEU**: Measures the overlap between the generated output and reference text based on n-grams.
- **ROUGE-1**: Measures the overlap of unigrams between the generated output and reference text.
- **BERT Score**: Evaluates the semantic similarity between the generated output and reference text using BERT embeddings.
- **Perplexity**: Measures how well a language model predicts the text.
- **Diversity**: Measures the uniqueness of bigrams in the generated output.
- **Racial Bias**: Detects the presence of biased language in the generated output.

## Testing

To run the tests, use the following command:

```
python -m unittest discover -s rag_evaluator -p "test_*.py"
```
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have any improvements, suggestions, or bug fixes, feel free to create a pull request (PR) or open an issue on GitHub. Please ensure your contributions adhere to the project's coding standards and include appropriate tests.

### How to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Run tests to ensure everything is working.
5. Commit your changes and push to your fork.
6. Create a pull request (PR) with a detailed description of your changes.

# Ouput

![image](https://github.com/Siddhartha082/Build-a-RAG-Evaluation-Tool-and-Python-Library/assets/110781138/abf49e78-cd55-4e28-9c35-320b8f3bbb9e)

![image](https://github.com/Siddhartha082/Build-a-RAG-Evaluation-Tool-and-Python-Library/assets/110781138/a8c80190-c07b-44c1-98f0-940fce6eeeb5)

![image](https://github.com/Siddhartha082/Build-a-RAG-Evaluation-Tool-and-Python-Library/assets/110781138/34ad65ab-841f-4dc2-b596-acc711e14a74)





## Contact

If you have any questions or need further assistance, feel free to reach out via [email](mailto:sai.siddharth@gmail.com).
