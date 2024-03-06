# demo-zenodo-neo4j-llm-ilvo
a demo presented by ILVO having the following steps:
- extracting metadata from soil related datasources in Zenodo as Dublincore standardised format,
- building knowledge graph of this metadata and uploading to local Neo4J database
- setting up LLM (CHATGPT) using open.ai API and integrating with Neo4J database to provide knowledge accessible via LLM, i.e. Retrieval-augmented generation (RAG) technique
- using Neo4J datascience algorithms for ranking or identifying duplicate datasources
