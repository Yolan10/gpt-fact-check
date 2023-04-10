# gpt-fact-check
A plugin for OpenAI plugin to fact-check information

# GPT-4 Fact Checker Plugin

This repository contains the GPT-4 Fact Checker plugin, which combines the power of OpenAI's GPT-4 language model with the Google Fact Check API to provide fact-checked responses to user prompts.

## Features

- Generates responses using the GPT-4 language model
- Extracts statements from the GPT-4 response
- Fact-checks statements using the Google Fact Check API
- Combines GPT-4 responses with fact-check results for a comprehensive output

## Requirements

- Python 3.6 or higher
- [openai](https://github.com/openai/openai) library
- [requests](https://docs.python-requests.org/en/latest/) library
- [spaCy](https://spacy.io/) library
- Google Fact Check API key
- OpenAI API key

## Installation

1. Clone this repository:
git clone https://github.com/yourusername/gpt4-fact-checker.git
cd gpt4-fact-checker


3. Set up your API keys:

- Obtain a Google Fact Check API key from the [Google Cloud Platform Console](https://console.cloud.google.com/)
- Obtain an OpenAI API key from the [OpenAI website](https://beta.openai.com/signup/)
- Replace the placeholders in the `gpt4_fact_checker.py` script with your actual API keys

## Usage

To use the GPT-4 Fact Checker plugin, simply run the `gpt4_fact_checker.py` script and provide your text or prompt:

python gpt4_fact_checker.py


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
