# Semantic_Search
Cognitive search using apache tika and ML as haystack and hugging face

**Environment setup as pre-requisite**

1. Install docker container desktop application for making the docker container as the local host.
2. Install jupyter notebook for building the cognitive search system.

----->Run the docker container application.

Haystack finds answers to queries within the documents are stored in a path provided. The current implementations of DocumentStore include ElasticsearchDocumentStore.You can start Elasticsearch on your local machine instance using Docker. Follow the below steps

___>Open command promt and run the code for activating the local server.
'docker run -d -p 9200:9200 -e "discovery.type=single-node" elasticsearch:7.9.2'

Further steps are covered in finalsemanticprediction.ipynb file. Extraction worked using Apache Tika by importing parcer.
