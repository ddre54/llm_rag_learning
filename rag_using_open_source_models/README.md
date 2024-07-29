# RAG Using open source models with Ollama

## Requirements

- [Install Jupyter Notebook](../README.md#requirements)
    - Create an virtual environment with `pyenv` and then install **Jupyter Notebook**
    - This is required for each project if you want to keep environments properly separated
- [Install - Ollama](https://ollama.com/)
    - Follow instructions to install Ollama CLI in your terminal
- [Downloadl - Model](https://ollama.com/library)


### Install model

For this project I'm using `Llama3.1`. This model could be pulled by default
when you install `ollama` cli.

You can check with:


```bash
ollama list
```

If the model wasn't pulled or you need to use a differnt model:

```bash
ollama pull llama3.1
```

### Running the model from Terminal

Running the selected model with `ollama` in the terminal:

```bash
ollama run llama3.1
```

**Note:** This is just to check that the model works. This is not needed since we will call
the model programmatically with `python`


## Setup

## References

- [LangChain - Installation](https://python.langchain.com/v0.1/docs/get_started/installation/)
- [PyPDF](https://pypi.org/project/pypdf/)

## Further Reads

- [DSPy - Prompt Optimization](https://github.com/stanfordnlp/dspy)
