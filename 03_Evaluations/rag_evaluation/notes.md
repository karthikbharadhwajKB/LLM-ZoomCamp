# RAG Evaluations

Evaluation and Monitoring comes hand in hand, they are quite closely related.

**Recap:** 

### Retrieval Evaluation: 

Evaluating Retrieval system: (figuring out which retrieval system works best for our domain and our data)....

**Metrics:**

1. hitrate
2. MRR

## `RAG` Evaluation: 

We will talk about evaluating RAG, but the things we talk here are generally apply to `LLMs`, basically work for evaluating quality of other LLM applications not only RAG.

Our main goal is to evaluate the whole RAG System in general..? or how good our prompt...?, or how good the llm we have used..?

Two Approaches to Evaluate the RAG System: 

1. **Offline Evaluation:**
   This approach involves evaluating the RAG system using a predefined dataset, often with ground truth answers. Metrics such as accuracy, recall, precision, or more specialized retrieval and generation metrics (e.g., hit rate, MRR, BLEU, ROUGE) are calculated without involving real users. Offline evaluation is useful for benchmarking, model selection, and rapid iteration.

   - **Cosine Similarity:** 
        How close the LLM generated answer to the answer we expect.. (ground truth)


   - LLM as a Judge


2. **Online Evaluation:**
   This method assesses the RAG system in a live environment with real users. It typically involves A/B testing, user feedback, or monitoring user interactions to measure system performance in production. Online evaluation helps capture real-world effectiveness, user satisfaction, and can reveal issues not apparent in offline tests.

   **Examples:** A/B testing, User feedback mechanism (thumbs up & thumbs down)

**Monitoring:**
Monitoring a RAG system means continuously tracking its performance and behavior in real time after deployment. This includes collecting metrics like response accuracy, latency, error rates, and user feedback. Monitoring helps detect issues early, ensures the system is working as expected, and provides insights for ongoing improvements.

- Observing the overall health of the system. (performance metrics: cpu utilization, ...)
- How good the answer is ..?



