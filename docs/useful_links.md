# File with useful links

## 1 - *txtai* links

txtai Github repo: https://github.com/neuml/txtai


RAG txtai Github repo: https://github.com/neuml/rag?tab=readme-ov-file

### 1.1 - Examples:

Main examples page: https://neuml.github.io/txtai/examples/ 

### 1.2 - Key points:

**Textractor** documentation: https://neuml.github.io/txtai/pipeline/data/textractor/

**Embeddings** documentation: https://neuml.github.io/txtai/embeddings/

**RAG** pipeline documentation: https://neuml.github.io/txtai/pipeline/text/rag/


## 2 - Models

### 2.1 - Embedding models:

Sentence-transformers models list: https://huggingface.co/models?pipeline_tag=sentence-similarity

#### 2.1.1: English

nli-mpnet-base-v2: https://huggingface.co/sentence-transformers/nli-mpnet-base-v2

all-MiniLM-L6-v2: https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2

#### 2.1.2: Spanish/Multilingual

paraphrase-multilingual-mpnet-base-v2: https://huggingface.co/sentence-transformers/paraphrase-multilingual-mpnet-base-v2

LaBSE: https://huggingface.co/sentence-transformers/LaBSE

#### 2.1.3: How to install and use sentence-transformers models:

<u>How to install sentence-transformers</u>:

``pip install -U sentence-transformers``

<u>How to use sentence-transformers</u>: 

```python
from sentence_transformers import SentenceTransformer
sentences = ["This is an example sentence", "Each sentence is converted"]

model = SentenceTransformer('sentence-transformers/paraphrase-multilingual-mpnet-base-v2')
embeddings = model.encode(sentences)
print(embeddings)
```



## 3 - Project ideas:

Analyzing the Stock Market with AI: 
https://medium.com/neuml/analyzing-the-stock-market-with-ai-df3a17ce0b4f

