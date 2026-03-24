resherForge AI: Agentic Resume Architect
An AI-powered career coach that transforms raw student experiences into industry-standard professional resumes using Google Gemini 2.0.

Project Overview
Most "freshers" struggle to translate their academic projects into professional language that passes Applicant Tracking Systems (ATS). FresherForge AI solves this by conducting a guided NLP interview with the user. It doesn't just "write" a resume; it "architects" one by refining basic descriptions into high-impact, action-oriented bullet points.

Key Features
Guided Interview Logic: Instead of a complex form, the bot asks one question at a time to reduce user friction.

LLM Refinement Engine: Implements a custom LangChain branch that upgrades "I did X" into "Executed X using Y, resulting in Z."

Production-Ready Security: Implemented Environment Variable management (.env) to ensure API security.

Clean Markdown Output: Generates a structured resume ready for PDF conversion.

Tech Stack
Core Logic: Python 3.12

AI Model: Google Gemini 2.0 Flash (via langchain-google-genai)

Orchestration: LangChain Core (v0.3+)

Environment Management: python-dotenv

Future Roadmap (SaaS Evolution)
[ ] Vector Memory (RAG): Integrate ChromaDB to suggest keywords based on specific Job Descriptions.

[ ] PDF Export: Automated conversion from Markdown to PDF.

[ ] Multi-Tenancy: Authentication layers to allow different users to save multiple resume versions.
