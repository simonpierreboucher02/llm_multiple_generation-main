# LLM Multiple Generation Notebook
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![GitHub Issues](https://img.shields.io/github/issues/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/issues)
[![GitHub Forks](https://img.shields.io/github/forks/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/network)
[![GitHub Stars](https://img.shields.io/github/stars/simonpierreboucher/llm-generate-function)](https://github.com/simonpierreboucher/llm-generate-function/stargazers)

This repository contains Jupyter notebooks demonstrating various generation tasks with Large Language Models (LLMs). It provides examples for summarization, text generation, few-shot learning, translation, and question-answering, utilizing different LLM APIs to showcase the capabilities of multiple providers.

## Repository Structure

- **[summarize_llm_function.ipynb](https://github.com/simonpierreboucher/llm_multiple_generation/blob/main/summarize_llm_function.ipynb)**: Demonstrates text summarization using LLMs, with examples for generating concise summaries from longer texts.
- **[generate_llm_function.ipynb](https://github.com/simonpierreboucher/llm_multiple_generation/blob/main/generate_llm_function.ipynb)**: Provides examples of text generation, covering creative and informative text outputs.
- **[fewshot_llm_function.ipynb](https://github.com/simonpierreboucher/llm_multiple_generation/blob/main/fewshot_llm_function.ipynb)**: Explores few-shot learning techniques, where the model is given a limited number of examples to guide its responses in specific tasks.
- **[translate_llm_function.ipynb](https://github.com/simonpierreboucher/llm_multiple_generation/blob/main/translate_llm_function.ipynb)**: Illustrates language translation capabilities using LLMs, allowing for translations across multiple language pairs.
- **[QA_llm_function.ipynb](https://github.com/simonpierreboucher/llm_multiple_generation/blob/main/QA_llm_function.ipynb)**: Demonstrates question-answering using LLMs, where the model provides accurate responses to queries based on context or a document.

## Getting Started

### Prerequisites

To run these notebooks, you will need:
- **Python 3.8+**
- **Jupyter Notebook**
- API keys for any relevant LLM services (e.g., OpenAI, Cohere, Anthropic)
- Required dependencies as listed in `requirements.txt`

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/simonpierreboucher/llm_multiple_generation.git
   cd llm_multiple_generation
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebooks

1. **Start Jupyter Notebook**: Open Jupyter by navigating to the repository folder and running:
   ```bash
   jupyter notebook
   ```
2. **Select a Notebook**: Open any of the notebooks (summarize, generate, few-shot, translate, or QA) to explore its functionality.
3. **Follow Instructions**: Each notebook includes instructions and code for working with LLMs in the context of specific generation tasks.

## Use Cases

- **Summarization**: Generate concise summaries for documents, articles, or other text inputs.
- **Text Generation**: Create new content, stories, or information-rich text with minimal input.
- **Few-Shot Learning**: Provide a few examples to guide the model's responses for targeted tasks, such as answering specific questions or following a template.
- **Translation**: Translate text across multiple languages using LLMs, useful for multilingual applications.
- **Question-Answering**: Use LLMs to provide context-based answers to questions, enhancing automated support or knowledge retrieval tasks.

## Contributing

We welcome contributions! Feel free to submit issues or pull requests to enhance functionality, add features, or address bugs.

## License

This repository is licensed under the MIT License.

