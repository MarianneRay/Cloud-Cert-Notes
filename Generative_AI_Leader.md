# Google Generative AI Leader Certification Exam Guide

The Google Generative AI Leader certification exam is designed for professionals who understand how to apply generative AI to transform businesses, focusing on strategic and responsible adoption rather than technical implementation. 

The 90-minute exam consists of 50-60 multiple-choice questions.

## Key Topics & Learning Path

### 1. Fundamentals of Generative AI (30% of exam)

**Identify Use Cases:** Know how gen AI can **create**, **summarize**, **discover**, and **automate** in real-world business scenarios, such as generating text, images, or code.

**Define Core Concepts:** 
Understand the differences between **AI** (broad field), **ML** (AI subset using data to learn), and **Generative AI** (ML that creates new content).

**Model Types**
- **Foundation Models** (FMs): Massive, versatile models trained on broad data, adaptable for many tasks (Gemini is an example).
- **Large Language Models** (LLMs): Foundation Models specialized in processing and generating human language (text and code).
- **Multimodal Models**: Models that can understand and generate content across multiple data types (e.g., text, image, video).
- **Diffusion Models**: Generative models primarily used for creating high-quality, realistic images and video.

**Data Types** 
- **Structured**: Data organized in tables
- **Unstructured**: Data without a fixed schema (text, video, audio)
- **Labeled**: Data tagged with a correct answer 
- **Unlabeled**: Raw data without predefined tags or categories

**Data Quality** 
- **Completeness**: The degree to which data is not missing or null for critical attributes.
- **Consistency**: The uniformity of data across the dataset and different systems (e.g., using the same units or formats).
- **Relevance**: The degree to which the data is applicable to the specific AI problem or business use case.

**Data Accessibility**: The ease with which data can be securely and reliably retrieved and used by AI systems.

**ML Lifecycle**: The iterative process of developing, deploying, and maintaining machine learning models.
- **Data Ingestion**: The process of **collecting and importing** raw data into the ML environment.
- **Data Preparation**: 	**Cleaning, transforming, and formatting** data to be ready for model training.
- **Model Training**: The iterative process of feeding data to the model to help it **learn patterns and make predictions**.
- **Model Deployment**: Making the trained model **available for use** in an application or service to generate predictions or content.
- **Model Management**: Monitoring the model's performance and data quality in production, and **updating/retraining** as needed.

### 2. Google Cloud's Generative AI Offerings (35% of exam)

**Google's Foundation Models** 
- **Gemini**: A family of multimodal models (text, image, audio) known for advanced reasoning and high-level performance.
- **Gemma**: A family of lightweight, open models built from the same research and technology as Gemini.
- **Imagen**: 	A model specialized in high-quality, realistic image generation from text prompts.
- **Veo**: A model specialized in creating high-quality, long-form, realistic video generation from text prompts.

**Generative AI Ecosystem**: The layers that constitute a Gen AI solution.
- **Infrastructure**: The underlying hardware (e.g., GPUs/TPUs) and cloud computing resources (e.g., Google Cloud) required to train and run models.
- **Models**: The trained machine learning algorithms (e.g., LLMs, FMs) that generate the new content.
- **Platforms**: Integrated cloud environments (like Vertex AI) that provide the tools for model development, customization, and deployment.
- **Agents**: AI entities (built on models) that use tools and a reasoning loop to automate complex, multi-step tasks.
- **Applications**: End-user products or features that utilize Gen AI models to deliver a specific function (e.g., a chatbot, a content summarizer).

**Key Google Cloud Tools** 
- **Vertex AI**: The unified Google Cloud platform for building, deploying, and managing the entire ML/Gen AI lifecycle.
- **Model Garden**: A catalog on Vertex AI offering discoverable, customizable models from Google, open-source, and third parties.
- **Generative AI Studio**: A no-code/low-code interface within Vertex AI for rapid experimentation, prototyping, and customizing models.
- **APIs**
    - **Speech-to-Text**: Converts spoken audio into written text.
    - **Cloud Vision**: Analyzes images to detect objects, faces, and text (OCR).
    - **Document AI**: Extracts structured data, such as key-value pairs, from unstructured documents (e.g., forms, invoices).

### 3. Techniques to Improve Model Output (20% of exam)

**Prompt Engineering**: The technique of structuring input (prompts) to guide a model to produce better, more relevant outputs.
- **Zero-shot**: A prompt that asks the model to perform a task without providing any examples of input/output.
- **One-shot**: A prompt that includes one example of the desired input/output to guide the model's response format.
- **Few-shot**: A prompt that includes a small number of examples of the desired input/output to guide the model.
- **Role prompting**: Instructing the model to act as a specific persona (e.g., "Act as a marketing expert") to shape the tone and content.
- **Chain-of-thought prompting (CoT)**: Instructing the model to show its step-by-step reasoning before giving the final answer to improve accuracy.

**Foundational Model Limitations**: Common challenges inherent in pre-trained large models.
- **Hallucinations**: The model generating false, nonsensical, or unfaithful information that sounds authoritative.
- **Bias**: The model reflecting and amplifying societal prejudices present in its training data.
- **the knowledge cutoff**: The date beyond which the model's original training data does not contain information, leading to a lack of current knowledge.

**Overcoming Limitations**: Methods to enhance model performance and reliability.
- **Grounding**: Anchoring the model's response to specific, verified data sources to reduce hallucinations and ensure factual accuracy.
    - **First-party**: Grounding the model using the organization's internal, proprietary data (e.g., private documents, databases).
    - **Third-party**: Grounding the model using licensed external data from vendors or partners (e.g., specialized industry reports).
    - **World data**: Grounding the model using public, up-to-date information (e.g., using Google Search) to address the knowledge cutoff.
- **Retrieval-Augmented Generation (RAG)**: A technique that retrieves relevant documents from a data store and inserts them into the prompt's context for grounding.
- **Fine-Tuning**: Further training a pre-trained model on a smaller, specific dataset to adapt it to a particular domain or task.
- **Sampling Parameters**: Settings that control the randomness and diversity of the model's output.
    - **Temperature**: Controls the creativity of the output; higher values lead to more random/diverse results.
    - **Top-P**: Controls the range of tokens the model considers for the next word; lower values restrict the choices to the most probable ones.

### 4. Business Strategies & Responsible AI (15% of exam)

**Strategic Implementation**: Steps for implementing a transformational gen AI solution
- Identifying business requirements: Define the specific problems or opportunities where Gen AI can deliver tangible value and a measurable return on investment (ROI).
- Measuring the impact of initiatives: Establishing Key Performance Indicators (KPIs), such as time saved, cost reduction, or increased user engagement, to quantify success.

**Responsible AI**: The practice of developing and deploying AI systems ethically, fairly, and securely.
- **Google's Secure AI Framework (SAIF)**: A set of guidelines and practices to manage risk and protect AI systems from malicious attacks and misuse throughout the lifecycle.
- **Managing Change**: Preparing the organization (people, processes) for the new AI-driven workflow; includes training, clear communication, and mitigating resistance.
- **Addressing bias and fairness**: Actively monitoring and mitigating systemic prejudice or unfair outcomes that could result from biased training data or model design.
- **Ensuring transparency**: Making the AI system's operation and limitations clear and understandable to users and stakeholders (Explainability).
- **Protecting privacy**: Implementing measures like data anonymization, pseudonymization, and strong governance to safeguard user data and comply with regulations.

**Agents**: Automated, reasoning entities built on models for complex automation.
- **Model**: The core Large Language Model (LLM) that acts as the agent's "brain" for understanding and generating language.
- **Reasoning loop**: The iterative process (e.g., ReAct framework) where the agent thinks (plans), acts (calls a tool), and observes (receives feedback) to complete a goal.
- **Tools**: External resources or APIs (e.g., databases, search engine, calculator) the agent can call and use to execute actions or retrieve information.
- **Use**: Automate complex tasks by breaking down multi-step processes into subtasks, calling relevant tools, and synthesizing the results to achieve a high-level objective (e.g., automated trip planning, customer service triage).
