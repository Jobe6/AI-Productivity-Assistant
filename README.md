# AI Workplace Productivity Assistant

## Project Overview
The AI Workplace Productivity Assistant is a modern, responsive web application designed to help professionals automate repetitive workplace tasks. By leveraging generative AI, the platform streamlines email drafting, meeting summarization, task planning, and research, ultimately saving time and increasing efficiency in the digital workplace.

## Features
The application includes an integrated dashboard with the following tools:
1. **Smart Email Generator:** Generates context-aware emails with tone adjustments (Formal, Friendly, Persuasive).
2. **Meeting Notes Summarizer:** Converts lengthy notes into concise summaries, extracting key decisions, action items, and deadlines.
3. **AI Task Planner / Scheduler:** Creates structured daily or weekly schedules, prioritizing tasks by urgency and importance.
4. **AI Research Assistant:** Summarizes topics and provides key insights and actionable recommendations.
5. **AI Chatbot Interface:** An interactive chat feature simulating a real workplace assistant.

## Tools Used
- **Lovable AI:** Used for generating the frontend UI/UX and building the application structure.
- **Generative AI Models (Gemini/ChatGPT):** Used behind the scenes for text generation, summarization, and research.
- **GitHub:** Used for version control and project documentation.

## Prompt Engineering Strategy (TCREI Framework)
To ensure high-quality outputs, all AI features are powered by structured system prompts using the TCREI framework:
- **Task:** Explicitly defining the AI's role (e.g., "Act as an executive assistant").
- **Context:** Providing background information (e.g., the target audience for an email).
- **References:** Providing examples or constraints (e.g., "Keep it scannable using bullet points").
- **Evaluate & Iterate:** Users are encouraged to review and edit all generated outputs. 

## Responsible AI Practices
We have implemented several safeguards to ensure responsible AI usage:
1. **Human-in-the-Loop:** All AI-generated text is placed in editable text boxes, ensuring the human user has the final say before using the content.
2. **Disclaimers:** A prominent disclaimer is displayed across the application: *"Notice: AI-generated content may contain errors or biases. Always review and verify outputs before use."*
3. **Privacy:** Users are advised not to input highly confidential personal or company information.

## Setup Instructions
This application is built as a web-based prototype. 
1. Navigate to the deployed Lovable AI link. 
2. Use the sidebar to navigate between the different productivity tools.
3. Input your prompt or text and click "Generate" to see the AI in action.
