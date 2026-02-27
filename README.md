# Parte I - promting engineering


# Instalación de Ollama
Se instala usando el siguiente link:
https://github.com/ollama/ollama

```
$ ollama
$ ollama run tinyllama
```

# Creación de un entorno virtual en conda

Instalar  miniconda: https://www.anaconda.com/docs/getting-started/miniconda/install#windows-command-prompt

```
$ conda create -n llms-env python=3.12
$ conda env list
$ conda activate llms-env

(llms-env) $ python -m pip install ollama
(llms-env) $ conda install -n llms-env ipykernel --update-deps --force-reinstall
```


# instalación de GRADIO

Link de gradio: https://www.gradio.app/

```
$ pip install gradio

```

# Parte II - fine-tuning

```
$ pip install huggingface_hub
$ pip install transformers datasets peft accelerate torch
```


# Parte III - RAG

```
$ pip install -qU langchain langchain-community langchain-ollama chromadb pypdf
```