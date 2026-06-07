# Lesson 1: Fundamentals of AI & ML

## Overview
This lesson introduces the core concepts of Artificial Intelligence (AI), Machine Learning (ML), Deep Learning (DL), and Generative AI. It builds a strong foundation for understanding how intelligent systems work and how AWS provides tools to build real-world AI/ML applications.

---

## Key Concepts

### Artificial Intelligence (AI)
AI is a broad field focused on building systems capable of performing tasks that typically require human intelligence such as reasoning, learning, and decision-making.

### Machine Learning (ML)
ML is a subset of AI that allows systems to learn from data and improve performance without being explicitly programmed.

### Deep Learning (DL)
DL is a subset of ML that uses neural networks (inspired by the human brain) to process complex patterns in data such as images, speech, and text.

### Generative AI
Generative AI is a subset of deep learning that can generate new content such as text, images, and code based on learned patterns.

---

## Machine Learning Workflow

1. **Data Collection & Preparation**
   - Quality of data is critical (“Garbage in, Garbage out”)

2. **Model Training**
   - Algorithms learn patterns from training data

3. **Evaluation**
   - Testing model performance and improving it

4. **Inferencing**
   - Using the trained model to make predictions

---

## Types of Data

### Labeled Data
- Data with known outputs
- Example: Image labeled as "cat" or "dog"

### Unlabeled Data
- Data without labels
- Used in unsupervised learning

---

### Structured Data
- Organized (tables, rows, columns)
- Examples:
  - Tabular data (CSV, databases)
  - Time-series data (stock prices)

### Unstructured Data
- No fixed format
- Examples:
  - Text
  - Images
  - Videos

---

## Types of Machine Learning

### Supervised Learning
- Uses labeled data
- Example: Email spam detection

### Unsupervised Learning
- Uses unlabeled data
- Finds hidden patterns
- Example: Customer segmentation

### Reinforcement Learning
- Learns via rewards & penalties
- Example: Self-driving cars, game AI

---

## Inferencing

### Batch Inferencing
- Processes large datasets at once
- Used for analytics

### Real-Time Inferencing
- Instant decision-making
- Used in chatbots, recommendation systems

---

## Deep Learning Fundamentals

- Built using **neural networks**
- Layers:
  - Input layer
  - Hidden layers
  - Output layer

### Applications:
- Computer Vision (image recognition)
- Natural Language Processing (chatbots, translation)

---

## Generative AI Fundamentals

### Foundation Models (FMs)
- Pre-trained on massive datasets
- Can perform multiple tasks:
  - Text generation
  - Summarization
  - Q&A

---

### FM Lifecycle
1. Data selection  
2. Pre-training (self-supervised learning)  
3. Optimization  
4. Evaluation  
5. Deployment  
6. Continuous improvement  

---

## Large Language Models (LLMs)

### Tokens
- Basic units of text (words/characters)

### Embeddings
- Numerical representations of meaning

### Vectors
- Capture relationships between words

- Enables models to understand context and generate human-like responses

---

## Diffusion Models
- Start with noise → generate meaningful output
- Used in image generation

---

## Multimodal Models
- Handle multiple data types (text + image)
- Example: Image captioning, AI assistants

---

## Model Optimization Techniques

### Prompt Engineering
- Designing inputs to improve output

### Fine-Tuning
- Training model on domain-specific data

### RAG (Retrieval-Augmented Generation)
- Uses external data without changing model weights

---

## AWS AI/ML Services Mapping

### Core ML
- **Amazon SageMaker** → Build, train, deploy ML models

### NLP & Text
- **Amazon Comprehend** → Text analysis
- **Amazon Translate** → Language translation
- **Amazon Textract** → Extract text from documents

### Conversational AI
- **Amazon Lex** → Chatbots

### Speech
- **Amazon Polly** → Text-to-speech
- **Amazon Transcribe** → Speech-to-text

### Vision
- **Amazon Rekognition** → Image & video analysis

### Search
- **Amazon Kendra** → Intelligent search

### Personalization
- **Amazon Personalize** → Recommendations

### Reinforcement Learning
- **AWS DeepRacer** → Hands-on RL

---

## Generative AI on AWS

- **Amazon Bedrock** → Access foundation models via API
- **SageMaker JumpStart** → Pre-built ML solutions
- **Amazon Q** → AI assistant for businesses
- **Amazon Q Developer** → AI coding assistant

---

## Real-World Use Cases

- Netflix → Recommendation systems (ML)
- ChatGPT → Generative AI (LLMs)
- Self-driving cars → Real-time inferencing
- Amazon → Personalized recommendations
- Amazon Rekognition → Face detection

---

## Key Takeaways

- AI is the umbrella; ML, DL, and GenAI are subsets  
- Data quality is the most critical factor in ML  
- Deep learning enables advanced capabilities like vision and language  
- Generative AI is powered by foundation models  
- AWS provides a complete ecosystem for AI/ML development  
- Prompt engineering and RAG are powerful, cost-effective optimization techniques  

---

## What's Next

Moving forward, I will:
- Apply these concepts in upcoming lessons
- Explore AWS AI/ML services hands-on
- Start building small real-world use cases

---
