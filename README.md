# Fine-Tuning GPT-3.5 Turbo for Answering Company Handbook Questions


## What This Project Does:

This project helps improve the GPT-3.5 Turbo model's ability to answer questions based on a company handbook. By fine-tuning the model with a dataset generated from the handbook, we aim to make it better at providing accurate and helpful answers to questions about the company's policies, procedures, and other information found in the handbook thus making it a valuable tool for employees and improving overall knowledge sharing within the organization.

## How to Use This Project:

### Setup:

1. Install Required Packages:

```bash
pip install langchain langchain-openai chromadb llama-index
```

2. Set Up Environment Variables:

To authenticate your API requests, you need to set up your environment variables for your [OpenAI](https://platform.openai.com/api-keys) and [Langchain](https://smith.langchain.com/o/62b71014-e718-5aff-a663-8a0f4862dcd7/settings) API keys. Replace "API_KEY_HERE" with your actual API keys:

```bash
OPEN_AI_API_KEY = "API_KEY_HERE"
LANGCHAIN_API_KEY = "API_KEY_HERE"
```

3. Clone the company handbook repository.

### How This Helps:

1. Employees can quickly find information in the handbook by asking the model questions.

2. Improves accessibility and understanding of the handbook content.
