# Comprison using RAG
## This is an on-going project to extract code using RAG.

1. Embedding each individual driver code and save them to Redis local database with an unique index name.
2. When querying, specify the index name of the target vector store to reduce the search space for the RAG.
3. For each device model, save the extracted code snippets to `.xlsx` file, which are compared later for similarity.

## Challenges

1. How to make sure the extracted code snippets are correct? Currently, it needs manual effort to achieve that.
2. Given two code snippets, how to calculate the similarity? Besides, how to identify new features that are benign or malicious?

### Redis Local Database
Check [Releases](https://github.com/XueningXu/RAG_Comparison/releases/tag/redis_local_database) to download the Redis local database.
