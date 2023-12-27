# Novel-Searcher-Backend
This repository contains backend code for the Nover Searcher project. The backend is implemented using Flask API.

![ezgif-3-6eeca39e6f](https://github.com/Grand-Blue-Dreaming/Novel-Searcher-Backend/assets/84507970/0a940537-215a-4b29-8379-4b05e11d2d1c)

## Features
- Search for books using plot queries.
- Returns to five results using semantic similarity matching by Dense Retrieval Model.

## Dense Feature Extraction Model
- DistilBERT finetuned on synthetic queries generated using DocTTTTTQuery

## Dataset / Index
- CMU Book summary dataset composed of book plot summaries from wikipedia
- Index created using FAISS nearest neighbor search library

## Future prospects
- Iterative improvements on user interaction
- Advanced filtering mechanism
