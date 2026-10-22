## 🚀 Live Demo

🌐 by [Launch NOVA — Student  Orbit]
(https://amazon-hackathon-project.vercel.app/)
# NOVA — Student Orbit

An independent **Alexa+-style simulated experience** for the 2026 Amazon Developer Hackathon. NOVA helps students organize tasks, generate study plans, and track learning progress through a conversational command interface.

## Run

Requires Node.js 20+. Run `npm install`, then `npm run dev`. Open http://127.0.0.1:5173/ . For a production build run `npm run build`.

## Demo script

1. Assistant: `add task Revise arrays`.
2. Assistant: `show my tasks`.
3. Assistant: `plan Python for 90 minutes`.
4. Switch to Planner to inspect the schedule.
5. Switch to Tasks and complete the task.
6. Refresh the browser: the task and plan should remain.
7. Assistant: `my progress`.
8. Optional: try microphone and response speech; depends on browser.

## Architecture and limitations

- React and Vite; no paid APIs, credentials, or cloud services required.
- Rule-based intent router simulates agentic tool dispatch for create_task, list_tasks, complete_task, create_study_plan, and get_progress.
- This is NOT connected to actual Alexa+, an Amazon developer account, or a generative AI service.
- Browser localStorage persists tasks, conversations, and plans per browser/origin. It is not cloud synchronization.
- Speech recognition is optional and browser-dependent; some browsers may send audio to external recognition services.
- Intended as the hackathon's *simulated Alexa+ experience* alternative, not as a self-hosted MCP server or Agent Skill. Refer to the official rules for eligibility and submission requirements.

## Feedback and judging

Include a public GitHub repository, public English YouTube/Vimeo video under 3 minutes, a detailed project description, and honest product/developer feedback in your Devpost submission. Explain the simulated route clearly. The project was developed with AI coding assistance; test and document what actually works before submission.

## License

MIT — see LICENSE.
