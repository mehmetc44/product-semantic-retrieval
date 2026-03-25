# Semantic Retrieval Demo

This project is a simple demo application showcasing **Semantic Search** and **RAG (Retrieval-Augmented Generation)**.  
The `Sentence-Transformers` library is used to convert product titles and descriptions into vectors, enabling meaning-based search.

---

## Features

- **Semantic Retrieval:** Represents the user query as a vector and retrieves the most semantically similar products.  
- **Vector DB (List):** A simple list-based vector database.  
- **Cosine Similarity:** Finds the most relevant products based on similarity score.  
- **RAG Demo:** Presents the vector search results in a fake LLM context for demonstration.

---

## Installation

```bash
# Install required libraries
pip install sentence-transformers numpy
```
## Usage:
```bash
Search: "I live in Berlin and it's so cold in winter here. I need something that can make me warm."
```
##### Output:
```bash
User Query: "I live in Berlin and it's so cold in winter here. I need something that can make me warm."

Relevant Products:
Blue Denim Jacket: Stylish blue denim jacket for casual wear
Red Running Shoes: Comfortable red running shoes for daily jogging

Suggested Product: Blue Denim Jacket
```
## Model

- **Model Name:** `all-MiniLM-L6-v2`  
- **Embedding Size(Dimension):** 384  
- **Purpose:** Ürün başlıkları ve açıklamalarını vektörlere dönüştürerek anlam temelli arama yapılmasını sağlamak.  
- **Use Case:** Semantic Retrieval, RAG tabanlı öneri sistemleri.  
- **Source / Documentation:** [Sentence-Transformers](https://www.sbert.net/)
