# Math Tutor Agent (Google ADK + Gemini)

An AI-powered Math Tutor Agent built using Google’s Agent Development Kit (ADK) and Gemini 2.5 Flash.
This agent helps students learn algebra by guiding them through step-by-step problem solving.

⸻

## Overview

The Math Tutor Agent is designed to act as a patient and supportive algebra tutor. Instead of simply giving answers, it:
• Guides students through problem-solving steps
• Encourages critical thinking
• Explains algebra concepts clearly
• Helps students correct mistakes

This project demonstrates how to build a conversational AI agent using the Google ADK and Gemini.

# Agent Configuration

from google.adk.agents.llm_agent import Agent

root_agent = Agent(
model='gemini-2.5-flash',
name='math_tutor_agent',
description='Helps students learn algebra by guiding them through problem-solving steps.',
instruction='You are a patient math tutor. Help students with algebra problems.'
)

## Features

    •	Conversational algebra assistance
    •	Step-by-step explanations
    •	Encourages student participation
    •	Uses Gemini 2.5 Flash for fast responses
    •	Lightweight single-agent architecture

⸻

## Prerequisites

    •	Python 3.10+
    •	Google ADK installed
    •	Google API key for Gemini

## Installation

    1.	Clone the repository:
    git clone <your-repo-url>
    cd math-tutor-agent

    2.	Install dependencies:
    pip install google-adk

    3.	Set environment variable:
    export GOOGLE_GENAI_API_KEY=your_api_key_here
    (Or create a .env file if using dotenv.)

## Running the Agent

Run the agent using ADK:
adk run
You should see:
Running agent math_tutor_agent
[user]:
You can now interact with the tutor.
Example:
Solve 2x + 5 = 15
Expected behavior:

The agent will guide the student through isolating x step by step instead of just giving the answer.

⸻
Example Interaction

User:
Solve 3x - 7 = 11
Agent:
Great question! Let's solve it step by step.

First, what should we do to isolate x?

## Project Structure

math-tutor-agent/
│
├── agent.py
├── README.md
└── requirements.txt

## Future Improvements

    •	Add multi-step problem tracking
    •	Add difficulty levels
    •	Add support for geometry and calculus
    •	Add tool integrations (graph plotting, equation solver)
    •	Store student session progress

⸻

Educational Purpose

This project is intended as a demonstration of how to build educational AI agents using Google ADK and Gemini models.

## 🙏 Acknowledgements

[Google Skills](https://www.skills.google/)
