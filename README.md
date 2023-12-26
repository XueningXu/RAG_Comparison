# Comprison using RAG
## This is an on-going project to extract code using RAG.

1. Embedding each individual driver code and save them to Redis local database with an unique index name.
2. When querying, specify the index name of the target vector store to reduce the search space for the RAG.
3. For each device model, save the extracted code snippets to `.xslx` file, which are compared later for similarity.
