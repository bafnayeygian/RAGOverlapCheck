# RAGOverlapCheck

Measure lexical overlap and redundancy between RAG chunks to identify duplicate context, excessive chunk overlap, and wasted retrieval budget.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/RAGOverlapCheck.git
cd RAGOverlapCheck
python -m pip install .
```

## Usage

```bash
rag-overlap-check --help
```

## Development

```bash
python -m unittest discover -s tests -v
```
