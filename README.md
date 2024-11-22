# Pokemon Story Image Generator

This project generates extended scenes from the Pokémon story, visualizes them in the style of anime comic strips, and combines them into a unified image. The generation pipeline leverages advanced NLP and image generation models to produce creative outputs.

## Models Used

### Embedding Model
- **Model**: `BAAI/bge-large-en-v1.5`
- **Capabilities**: 
  - Multilingual support, including Chinese.
  - Ideal for medical dialogue datasets like [MedDialog](https://paperswithcode.com/dataset/meddialog#:~:text=Medical%20Dialogue%20Datasets-,The%20MedDialog%20dataset%20(Chinese)%20contains%20conversations%20(in%20Chinese),more%20dialogues%20will%20be%20added.).

### Language Model
- **Model**: `Mistral-7B-Instruct-v0.2`
- **Features**:
  - Fine-tuned instruct version.
  - Enhanced generation capabilities for interactive storytelling.

## Dependencies

Install the required dependencies with the following commands:

```bash
pip install llama-index-embeddings-huggingface
pip install llama-index-llms-llama-cpp
pip install llama-cpp-python
pip install llama-index-embeddings-langchain
pip3 install huggingface-hub
pip install langchain
pip install transformers --upgrade
pip install -U langchain-nomic
