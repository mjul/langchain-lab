# LangChain Lab
Repo for LangChain experiments.

- [`langserve_demo.py`](langserve_demo.py) demonstrates how to use LangServe to generate text and APIs for the language models. 

## Installation

This project uses Python 3.11.

You can install LangChain and its CLI tooling including LangServe with `pip`:

```
    pip install langchain langchain-cli
```

Also, access to a language model is required, e.g. the OpenAI GPT models via the API:

```
    pip install openai
```

Alternatively, you can install all the dependencies from the `requirements.txt` file:

```
    pip install -r requirements.txt
```

The documentation is here: https://python.langchain.com/docs/get_started/installation