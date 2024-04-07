# RAG
## Definition
- retrieval(检索) augmented generation: combine retrieval and generation, Leveraging **external knowledge bases** to enhance LLM performance
## Principle
- knowledge source -> vector-DB
  query -> retrieval -> vector-DB
  retrieval -> generation
## Optimization
- enhance the quality of DB
  - embedding optimization: multi-task
  - indexing: meta data
- query
- context: rerank.eg
- retrieval
  - iterative retrieval
  - recursive retrieval: chain of thought
  - adaptive retriveval: Flare, self-RAG
- LLM fine-tuning
## RAG vs. Fine-tuning
- RAG
  <img width="645" alt="Screenshot 2024-04-07 at 11 17 48" src="https://github.com/LongLiveForFreedom/InterLM_Homework/assets/89987363/8dd2d893-c3ce-4704-96a6-2c48e5aa8532">

- Fine-tuning
  <img width="650" alt="Screenshot 2024-04-07 at 11 18 16" src="https://github.com/LongLiveForFreedom/InterLM_Homework/assets/89987363/becb95ec-d3a7-4bc0-8ec5-29aafdd8ab5e">
## Metrics
acc, recall, f1 score, bleu, rouge
tool: RAGAS, ARES, TruLens
