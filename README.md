# CareConnect Assistant

A front-desk chatbot for a fictional clinic (Jerusalem Clinic), built with Python, the OpenAI API, and Gradio.

**Author:** Leul Tsige | **Course:** CS529 AI Engineering

## What it does
- Answers questions about clinic hours, services, insurance, and appointments
- Uses `clinic_info.txt` as its only source of facts
- Refuses medical advice and directs emergencies to 911
- Remembers the conversation and validates user input

## Files
- `CareConnectChatbot.ipynb`: the main notebook, with code, tests, and documentation
- `clinic_info.txt`: the clinic data
- `images/`: screenshots of the UI

## How to run
1. Install the dependencies:
```
   uv sync
```
2. Create a `.env` file:
```
   OPENAI_API_KEY=your-key-here
```
3. Open the notebook, select the `.venv` kernel, and run all cells.

## Tools
Python, OpenAI API (gpt-4o-mini), Gradio 6, uv
