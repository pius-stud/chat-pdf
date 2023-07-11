# Chat-pdf

This repository contains the python scripts useful to create a ChatBot on VSCode.\
The ChatBot was made using the LLM from OpenAI "gpt-3.5-turbo" and also thanks to the python libraries Langchain and Llama-index.\
\
Thanks to these scripts is possible to load more PDF files and to query the ChatBot in order to obtain information about them.\
This is done creating indexes (and/or a graph) from each pdf file that can be queried.\
\
The Scripts folder is composed of different files:
- **chatdocu.py**: if you want to run a website-like chat with your pdfs.
- **envchatdocu.yaml**: Anaconda environment with the needed libraries.
- **query_composable_graph.py**: Querying multiple index (PDF files) at once to obtain a response built from them.
- **query_index_basic.py**: The simplest way. Load a PDF file, build an index, and ask questions about it.
