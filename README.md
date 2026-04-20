# AI Powered Web Application - ELI5 Explainer

A lightweight AI web app that turns complex topics into simple, child-friendly explanations.

This project demonstrates practical prompt engineering, API integration, responsive UI design, and clean user feedback handling in a minimal front-end setup.

## What This Project Does

Users enter any difficult topic (for example, "blockchain" or "neural networks"), and the app calls an LLM API to return a short, easy-to-understand explanation in plain language.

## Why This Project Matters

- Solves a real communication problem: making technical ideas understandable.
- Shows how AI can improve learning and accessibility.
- Highlights end-to-end product thinking in a compact project (UI + API + UX states).

## Key Features

- Simple one-page interface for fast interaction
- AI-generated "Explain Like I'm 5" responses
- Loading, success, and error state handling
- Enter key support for quick submissions
- Mobile-friendly responsive layout

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- OpenRouter Chat Completions API

## Project Structure

```text
.
├── index.html   # Complete UI + logic in one file
└── README.md
```

## How To Run Locally

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-folder>
   ```
2. Open `index.html` in your browser.
3. Add your own API key in the script section where `API_KEY` is defined.
4. Type a topic and click **Explain It**.

## Recruiter Notes

This project reflects the ability to:

- Build a functional AI product from scratch
- Integrate external AI APIs and handle response parsing
- Design clear UX around asynchronous operations
- Keep implementation lightweight and easy to deploy

## Suggested Improvements (Next Iteration)

- Move API calls to a backend service to protect API keys
- Add explanation difficulty levels (kid, beginner, advanced)
- Add topic history and favorite explanations
- Improve model selection and prompt customization

## Author

**Name:** Your Name  
**Role:** B.Tech Student, IIT Roorkee  
**Interests:** AI, full-stack web development, real-world product building

---

If you are a recruiter or hiring manager, I would be happy to walk you through architecture decisions, API design choices, and possible production upgrades for this app.
