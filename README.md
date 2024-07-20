# Requirements

- Python 3.12.2

Activate the environment:

```bash
# virtual environments from pyenv
pyenv install 3.12.2
pyenv virtualenv 3.12.2 llm_rag_learning
pyenv activate llm_rag_learning
pyenv deactive
# You can also use `pyenv local`
```

Install Jupyter:

```bash
pip install jupyterlab
```

Install Jupyter Notebooks:

```bash
pip install notebook
```

Install Voila:

```bash
pip install voila
```

Install Jupyter Widgets:

```bash
pip install ipywidgets
```

Resources:
- [Jupyter Notebooks - Install](https://jupyter.org/install)
- [Jupyter Widgets:](https://ipywidgets.readthedocs.io/en/stable/user_install.html)


Install `requirements.txt` (`openai`, `langchain`, `langchain_pinecone`, etc)
```bash
pip install -r requirements.txt
```

Create a OpenAI API account [here](https://platform.openai.com/login), get and set your API project key in your `.env` file

```bash
OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
```

Create a free Pinecone account [here](https://www.pinecone.io/), get and set your API key in your `.env` file

```bash
PINECONE_API_KEY = [ENTER YOUR PINECONE API KEY HERE]
PINECONE_API_ENV = [ENTER YOUR PINECONE API ENVIRONMENT HERE]
```

Notes:
- `PINECONE_API_ENV`: Set to the Project ID


# Run Environment

Run Jupyter Lab:

```bash
jupyter lab
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Run Voila:
```bash
voila
```

# Projects

- [Youtube video to transcript to RAG on LLM using OpenAI and Pinecone - Tutorial](youtube-videos-rag.ipynb)
- [Youtube video to transcript to RAG on LLM using OpenAI and Pinecone - Clean version](youtube-videos-rag-clean.ipynb)

# Resources/Credits:

- [Building a RAG application from scratch using Python, LangChain, and the OpenAI API](https://www.youtube.com/watch?v=BrsocJb-fAo)
- [Building a RAG application from scratch - GitHub](https://github.com/svpino/youtube-rag)
- [Build a Retrieval Augmented Generation (RAG) App](https://python.langchain.com/v0.2/docs/tutorials/rag/)
- [Build a Question/Answering system over SQL data](https://python.langchain.com/v0.2/docs/tutorials/sql_qa/)

