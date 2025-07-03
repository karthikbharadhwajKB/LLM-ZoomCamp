## Ground Truth / Gold Standard dataset:  

A ground truth dataset in machine learning is a collection of data that has been manually labeled or verified to be correct. It serves as the "gold standard" against which models are trained and evaluated. For example, in a classification task, the ground truth dataset contains input samples and their correct labels, allowing you to measure how well your model predicts the true outcomes.


### Promblem Statement: Information Retrieval / Document Retrieval 

#### Task: We will be given with a query (probably in natural language) we need to retrieve relevant documents from the vector store. 

We might have 1000 Queries... 

#### Example: 
Query: I discovered the course. Can I still join ? 

Relevant documents: doc1, doc2, doc3,....

* For one query, you might have multiple relevant documents. 


### Simplication: 

Query: I discovered the course. Can I still join ? 

Relevant documents: doc1 (single document with high relevance score).


### Dataset Generation Process: 

for each record in FAQ: 
    generate 5 questions

**Outcome:**
1000 records => 5000 questions

### Approaches to Creating This Dataset:

1. **Traditional Approach:**  
   A human evaluator or domain expert reviews user queries and manually labels which documents are relevant for each query.  
   This method produces high-quality, accurate ground truth data, but it is time-consuming and requires significant domain expertise.

2. **User Interaction Observation:**  
   Collect real user queries and observe which documents the system retrieves.  
   Evaluate the relevance of these results, either manually or through user feedback, to build the dataset.

3. **LLM-Based Generation (Our Approach):**  
   In this project, we will use a Large Language Model (LLM) to automatically generate queries and their corresponding relevant documents, streamlining the dataset creation.