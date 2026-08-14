# Annotated Vector Database & ChromaDB Tutorial

Personal annotated notes and hands-on implementations from the 
**IBM RAG for Generative AI Applications Specialization** 
(Coursera) — specifically the "Vector Databases for RAG" module.

Each notebook combines clear concept explanations with working 
code — written to be readable by anyone learning this topic.

---

## Structure

### 📁 1 - Vector Database Concepts
| Notebook | Topics Covered |
|---|---|
| `1_vectordb_concepts.ipynb` | What is a vector, vector databases vs traditional databases, similarity search, distance metrics (L2, cosine, dot product), vector DB types, applications |

### 📁 2 - ChromaDB
| Notebook | Topics Covered |
|---|---|
| `2.1_chromadb_keyconcepts_architecture.ipynb` | ChromaDB architecture, deployment modes, workflow, integrations |
| `2.2_chromadb_filtering.ipynb` | Metadata filtering, document filtering, filter operators ($eq, $ne, $gt, $in, $nin, $and, $or) |
| `2.3_similaritysearch_&_hnsw_chromadb.ipynb` | Similarity search in ChromaDB, HNSW index, configuration parameters |
| `2.4_CRUD_chromadb.ipynb` | Full CRUD operations — add, get, update, upsert, delete, collection-level operations |
| `ChromaDB_SimilaritySearchProject.ipynb` | End-to-end similarity search project using ChromaDB and sentence-transformers |

---

## Tech Stack
- Python 3.10
- ChromaDB
- Sentence Transformers (`all-MiniLM-L6-v2`)
- NumPy / PyTorch

---

## Who this is for
Anyone learning Vector Databases and ChromaDB for RAG applications 
— especially if you find official docs too sparse or course 
materials too surface-level. These notebooks go deeper on the 
"why" behind each concept, not just the "how."

---

## Related
Also check out my annotated HuggingFace LLM Course & LlamaIndex Course:  
👉 [Annotated-HuggingFace-LLM-Course](https://github.com/rehan-ml/Annotated-HuggingFace-LLM-Course)

👉 [Annoted-LlamaIndex-Tutorial](https://github.com/rehan-ml/LlamaIndex-Tutorial)

---

## Author
**Rehan Raza**  
Building toward an Applied AI/ML Engineer role — sharing 
everything I learn along the way.
