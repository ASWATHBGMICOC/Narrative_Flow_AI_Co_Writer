Narrative Flow: AI-Co-Writer
Narrative Flow is an interactive co-writing ecosystem that bridges the gap between human creativity and Large Language Models. By leveraging Llama 3 and Streamlit, the application provides a low-latency environment for generating cohesive, context-aware narratives.

Project Objective
The primary goal is to evaluate the efficacy of lightweight LLM integration in creative workflows. Narrative Flow demonstrates how prompt engineering and session management can transform a standard LLM into a specialized creative partner capable of maintaining narrative arc and stylistic consistency.

System Architecture
1.  Context Injection: User prompts are merged with genre-specific system instructions.
2.  Inference Engine: Llama 3 processes the tokens to generate high-fidelity prose.
3.  State Management: Streamlit’s session state tracks the story history to ensure long-range coherence.
4.  UI/UX Layer:A clean, chat-inspired interface built for distraction-free writing.

Technical Stack
Backend (Python 3.10+):Acts as the core orchestration layer, managing application logic, data flow, and session persistence to ensure story continuity.
Inference Engine (Meta Llama 3): Provides the underlying linguistic intelligence, responsible for high-fidelity natural language generation and complex narrative reasoning.
User Interface (Streamlit):Powering the frontend, this framework enables a responsive, interactive web environment for real-time storytelling and rapid deployment.
Orchestration (Prompt Engineering):Employs advanced prompting strategies to sit between the user and the LLM, optimizing the model's output for creative depth and stylistic consistency.

Key Features
Adaptive Persona Engine: Instantly switch between genres with tuned system prompts.
Real-Time Co-Authorship: An interactive loop where the user provides "beats" and the AI expands them into full scenes.
Session Persistence: Maintains a sliding window of story context, preventing the AI from "forgetting" earlier plot points.
Minimalist Workspace: A sleek UI designed to prioritize the writing process over complex configurations.

Research & Insights
This project serves as a practical implementation of several NLP concepts:
Model Quantization: Testing the viability of running Llama 3 on consumer-grade hardware for creative tasks.
Prompt Chaining: Using structured templates to guide the LLM's "imagination" without losing logical flow.
Human-in-the-Loop (HITL): Studying how user corrections influence subsequent AI-generated story branches.

Future Development
NLP Coherence Scoring: Integrating metrics to quantify narrative "flow" and vocabulary diversity.
Vector Database Integration: Implementing RAG (Retrieval-Augmented Generation) for world-building "bibles."
Multi-Modal Export: Features to export drafts directly to Markdown or PDF formats.
