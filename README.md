# calGPT: LLaMa Fine-tune Medical Chatbot

## Usecase
This Chatbot is currently covering the Medical Field and not limited to any other use case as well, so feel free to use your custom dataset for your own use case

## Tech Stack
Model Used
* LLaMa 7b HuggingFace

Embeddings 
* all-MiniLM-L6-v2

Vector Datastore
* FAISS


## Installation

Make sure to download LLaMa-7B model from HuggingFace, then store it within the same directory
then run:

`pip install -r requirements.txt`

Run

`chainlit run main.py -w`


