# AIChatbot-Medical-2.0
## **AI Chatbot for Medical Domain - Fine-tuning DeepSeek-R1**

This repository demonstrates how to fine-tune the DeepSeek-R1 model, a distilled version of the Llama model, to create an AI-powered chatbot specifically for answering medical-related queries. The model leverages Low-Rank Adaptation (LoRA) for efficient fine-tuning and 4-bit quantization to reduce memory usage, making it deployable on GPUs with limited memory.

### **Features**

**Medical Knowledge Chatbot:** Fine-tuned for providing answers to medical queries, explaining symptoms, treatments, and healthcare topics.

**Efficient Fine-tuning:** Uses Low-Rank Adaptation (LoRA) to reduce memory and computational costs during the training process.

**Memory Efficient:** Utilizes 4-bit quantization for reduced memory consumption, enabling the model to run on GPUs with limited VRAM.

**Optimized for Real-World Usage:** Trained with medical-specific datasets to improve interaction quality for healthcare-related conversations.

## **Setup and Installation**

### **Prerequisites**

Python 3.7 or higher

CUDA-enabled GPU (preferably 14GB VRAM or more)

### **Dependencies:**

torch

transformers

datasets

peft

trl

### **Usage**

**Load the Model:** The model is based on DeepSeek-R1, a distilled version of the Llama model. It is configured to run in 4-bit precision for memory efficiency.

**Fine-tune the Model:** The model is fine-tuned using Low-Rank Adaptation (LoRA), which enables efficient adaptation to the medical domain without retraining the entire model.

**Dataset:** A small dummy dataset is included for demonstration purposes. You can replace this with a more comprehensive medical dataset that includes questions and answers related to health, symptoms, treatments, and more.

**Training:** The model is trained for a few epochs with minimal steps to showcase the fine-tuning process. Adjust the number of epochs and training steps based on the size of your dataset.



