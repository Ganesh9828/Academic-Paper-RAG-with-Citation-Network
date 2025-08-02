#  Academic Paper RAG with Citation Network

This project implements a Retrieval-Augmented Generation (RAG) system tailored for academic papers, enhanced with a citation network to enable better contextual understanding and trend analysis.

##  Features

- Vector-based retrieval system for academic papers.
- Citation network utilities to map and analyze references.
- Trend analysis module for identifying emerging topics.
- Modular architecture for future extension.
- Built with simplicity and academic research in mind.

##  Project Structure


Nervesparks/
├── app.py                   
├── citation_utils.py         
├── citation_utils(build).py 
├── retrieval.py            
├── trend_analysis.py        
├── vector_db.py          
├── requirements.txt         


## 🛠 Installation

1. Clone the repository or unzip the project.

bash
git clone <https://github.com/Ganesh9828/Academic-Paper-RAG-with-Citation-Network/>
cd Academic-Paper-RAG-with-Citation-Network/Nervesparks


Install dependencies.

```bash
pip install -r requirements.txt
```

##  How It Works

1. **Document Vectorization**: Academic documents are processed and stored in a vector database.
2. **RAG Pipeline**: User queries are matched with relevant documents using semantic similarity.
3. **Citation Network**: Each document's references are mapped to understand influence and context.
4. **Trend Analysis**: Analyzes citation frequency and topic growth over time.

##  Use Cases

- Research assistance tools
- Academic trend monitoring
- Citation influence mapping
- Knowledge graph enrichment

##  TODO

- Add frontend UI for interaction
- Integrate academic paper source (e.g., arXiv API)
- Improve citation disambiguation

##  License

This project is for educational and research purposes.

---

**Author**: *Ganesh Cheruku*
