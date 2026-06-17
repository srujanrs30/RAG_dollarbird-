# RAG_dollarbird-
A local RAG application for company knowledge retrieval using semantic chunking, BGE-M3 embeddings, ChromaDB, cross-encoder reranking, and relevance guardrails to prevent out-of-context answers.

# step by step guide to run this:
# step 1: download "website1.md" file.
# step 2: run the "chunking embedding and storing.ipynb" file - this will prepare the chunks, perform embeddings and store it inside vectordb.
# step 3: run "RAG without guardrails.ipynb" file to perform rag operation on the stored embeddings.
(step 3 only shows the basic version of the rag it does not contain guardrail operations)
# step 4(optional step): here i have performed 2 guardrails, you can run anyone or both based on your requirement.
# note: you can either skip step 3 or step 4.
