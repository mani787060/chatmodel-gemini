# Google Gemini API Integration

## 🚀 Project Overview
This repository demonstrates how to leverage **Google's Gemini** models through the `google-generativeai` SDK. The project covers the core aspects of the Gemini ecosystem, including text generation, vision-based reasoning (multimodality), and maintaining stateful chat history using the built-in `start_chat` interface.

---

## 🛠️ Key Features

### 1. Generative Model Orchestration
* **Gemini Pro:** Utilizing the text-optimized model for complex reasoning and content generation.
* **Gemini Flash:** Implementation for low-latency, high-speed interaction.
* **Multimodal Capabilities:** Sending images alongside text prompts for visual understanding and analysis.

### 2. Advanced Chat Interface
* **Stateful Chat Sessions:** Using the `chat_session` object to handle conversation history automatically without manual array management.
* **Streaming Responses:** Implementing real-time text generation for a more fluid user experience.

### 3. Safety & Configuration
* **Safety Settings:** Customizing thresholds for harassment, hate speech, and sexually explicit content to ensure responsible AI usage.
* **Generation Config:** Fine-tuning `temperature`, `top_p`, and `candidate_count` to control response diversity.

### 4. Developer Best Practices
* **Environment Security:** Securely loading `GOOGLE_API_KEY` from `.env` files.
* **Resource Management:** Handling API exceptions and connection timeouts.

---

## 💻 Tech Stack
* **Language:** Python
* **SDK:** `google-generativeai`
* **Utilities:** `python-dotenv`, `PIL` (Python Imaging Library for Vision tasks)
* **Platform:** Jupyter Notebook / Google Colab
