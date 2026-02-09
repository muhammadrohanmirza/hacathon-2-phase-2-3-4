TASKOO AI
==============================
Spec-Driven Fullstack AI Task Assistant
--------------------------------------

Taskoo AI is an intelligent task management system that allows users to manage
their daily tasks using natural language instead of traditional buttons and forms.

It is designed with a modern, stateless architecture and powered by AI Agents
that understand user intent and execute actions using a standardized protocol.

--------------------------------------------------
WHAT MAKES TASKOO AI DIFFERENT?
--------------------------------------------------

• Talk to your task manager like a human
• No rigid UI flows or complex forms
• AI understands context and follow-up commands
• Secure, scalable, cloud-ready architecture
• Built using spec-driven development principles

Example:
“Remind me to call the client tomorrow at 6pm”
“Delete the last completed task”

--------------------------------------------------
CORE FEATURES
--------------------------------------------------

- Natural Language Task Management
- AI Agent powered reasoning & intent detection
- Model Context Protocol (MCP) for tool execution
- Secure stateless authentication (Better Auth)
- Serverless-ready backend
- Clear separation of frontend, backend, and AI logic

--------------------------------------------------
SYSTEM OVERVIEW
--------------------------------------------------

User interacts with a Next.js frontend.
Authentication is handled using JWT via Better Auth.
Requests are sent to a FastAPI backend.
An AI Agent processes the request.
If needed, the agent calls MCP tools.
Tasks are stored and managed in PostgreSQL (Neon).
A natural language response is returned to the user.

--------------------------------------------------
TECH STACK
--------------------------------------------------

Frontend:
- Next.js (React)
- Tailwind CSS
- Vercel AI SDK

Backend:
- FastAPI (Python 3.11+)
- SQLModel
- OpenAI Agents SDK
- Model Context Protocol (MCP)

Infrastructure:
- Neon PostgreSQL
- Better Auth
- Pydantic Validation

--------------------------------------------------
LOCAL SETUP (SUMMARY)
--------------------------------------------------

Backend:
1. Create virtual environment
2. Install dependencies
3. Configure environment variables
4. Initialize database
5. Run FastAPI server

Frontend:
1. Install dependencies
2. Configure environment variables
3. Run migrations
4. Start development server

--------------------------------------------------
USAGE EXAMPLES
--------------------------------------------------

Add a task:
“Add a task to submit the report by Friday”

List tasks:
“What tasks are pending today?”

Update task:
“Mark the report task as high priority”

Complete task:
“Mark the grocery task as done”

Contextual command:
“Delete the last task”

--------------------------------------------------
CONTRIBUTING
--------------------------------------------------

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to GitHub
5. Open a Pull Request

--------------------------------------------------
LICENSE
--------------------------------------------------

MIT License

--------------------------------------------------
Built with passion during a Spec-Driven Development Hackathon
--------------------------------------------------
