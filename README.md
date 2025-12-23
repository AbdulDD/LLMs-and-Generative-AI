# LLMs and Generative AI

# Generative AI Project Lifecycle

A Generative AI project can be broadly divided into three major stages:
1. Scope & Model Selection
- Clearly define the business problem or use case before starting development.
- Identify success metrics and constraints (cost, latency, accuracy, compliance).
- Model selection criteria:
    1. Pretraining alignment: How well the model’s pretraining data and objectives align with your domain and task.
    2. Model size: Trade-offs between performance, inference latency, and computational resources.
    3. Context window: Maximum input length supported by the model, which impacts document handling, reasoning depth, and memory.

2. Adaptation & Alignment
- Prompt engineering
- Fine-tuning or parameter-efficient tuning (e.g., LoRA)
- Retrieval-Augmented Generation (RAG)
- Safety, bias, and alignment adjustments
- The goal is to improve task performance while ensuring reliability and responsible behavior.

3. Application Integration
- API or service integration
- Frontend and user experience design
- Monitoring, logging, and evaluation
- Cost optimization and scalability
- Deployment and maintenance