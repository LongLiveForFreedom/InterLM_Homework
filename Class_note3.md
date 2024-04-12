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
# Huixiangdou
- 智能客服：技术支持、领域知识对话
  - 群组中存在闲聊
  - parse users' intent
- protocol: BSD-3-Clasue
- workflow
  <img width="382" alt="Screenshot 2024-04-12 at 09 13 21" src="https://github.com/LongLiveForFreedom/InterLM_Homework/assets/89987363/d08b0db2-ad90-44a5-b13b-ebba91356c8e">
  <img width="582" alt="Screenshot 2024-04-12 at 09 13 48" src="https://github.com/LongLiveForFreedom/InterLM_Homework/assets/89987363/beaf0091-3f9c-41b6-919e-053b9611f568">

