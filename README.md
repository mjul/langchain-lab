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

### LangChain CLI

The above installs the `langchain` CLI. It can create and manage apps and templates, for information try:

```
    langchain --help
```

You can create a new LangChain app from a template, e.g. in the `demo_app` directory:

```
    langchain app new demo_app
```

You can add packages from the LangChain registry, e.g. the `rag-chroma-private` package:

``` 
    langchain app add rag-chroma-private
```

For more information, see https://python.langchain.com/docs/templates/
