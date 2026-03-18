# AI Agent Conversation Generator

## Overview
This project simulates multi-turn conversations between users and AI assistants using function-calling tools such as calendar, email, and maps APIs.

The dataset is designed for training and evaluating Large Language Models (LLMs) in tool usage, reasoning, and real-world task completion.

---

## Tools
- Calendar API → create_event
- Email API → send_email
- Maps API → find_location

---

## Conversation Structure
Each conversation follows this flow:

User → Assistant → Tool → Assistant

---

## Objectives
- Demonstrate correct tool selection
- Extract structured arguments from natural language
- Simulate realistic user-assistant interactions
- Handle both valid and invalid requests

---

## Project Structure
conversations/ → Multi-turn dialogue datasets
tools/ → API definitions
---

## Use Cases
- LLM training datasets
- Function-calling evaluation
- AI assistant simulation

---

## Skills Demonstrated
- JSON structuring
- API reasoning
- LLM behavior simulation
- Multi-turn dialogue design