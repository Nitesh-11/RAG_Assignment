# Retrieval Augmented Generation

In this project ollama is used to perform local inferencing of the Mistral LLM.
Download the the ollama from the website as per your PC requirements -https://ollama.com/
Once ollama is downloaded install the setup and run the command - `ollama run mistral` then follow the below steps to execte the RAG pipeline

# Steps to run 

1. Clone the repo - `git clone https://github.com/Nitesh-11/RAG_Assignment.git`
2. Create the virtual environment using venev - `python -m venev env`
3. Activate the environment - `env\Scripts\activate` or `env\Scripts\activate.bat`
4. Install the requirements - `pip install requirements.txt`

## Creating the Embeddings earlier and the executing the chatbot

To create the embedding and then query the PDF Data using chatbot includes 2 steps, creating the embeddings and storing the data. Two steps to do this are
1. Create Embeddings using - `python vectorStore.py`
2. Execute the chatbot using chainlit - `chainlit run chatVectorDB.py`

## Providing the oprtion to upload the file and then query using chatbot interface.

To create the embedding and then query the PDF Data using chatbot includes 2 steps, creating the embeddings and storing the data. Two steps to do this are
1. Execute the chatbot using chainlit - `chainlit run rag_upload.py`
