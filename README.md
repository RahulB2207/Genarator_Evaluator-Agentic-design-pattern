
## AI Persona Chatbot using Generator-Evaluator Agentic Design Pattern

An AI-powered chatbot built using the Generator-Evaluator Agentic Design Pattern where the system answers user queries by acting as me based on my LinkedIn profile and professional summary.

The project uses:

GPT-4o-mini as the Generator Agent
GPT-4o as the Evaluator Agent

The evaluator checks whether the generated response is accurate, relevant, and aligned with my background. If the response is not acceptable, feedback is provided and the response is regenerated automatically.

## 🧠 Agentic Workflow

                User Query
                     │
                     ▼
        ┌────────────────────┐
        │ Generator Agent    │
        │ (GPT-4o-mini)      │
        └────────────────────┘
                     │
                     ▼
          Generated Response
                     │
                     ▼
        ┌────────────────────┐
        │ Evaluator Agent    │
        │ (GPT-4o)           │
        └────────────────────┘
                     │
       ┌─────────────┴─────────────┐
       │                           │
       ▼                           ▼
    Response Accepted         Feedback Generated
       │                           │
       ▼                           ▼
    Final Response           Regenerate Response

  ## Demo
  <img width="941" height="398" alt="image" src="https://github.com/user-attachments/assets/01bc99ce-be34-474b-b828-686a28555099" />

