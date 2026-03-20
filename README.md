# 🤖 ReAct Agent – AI Agents Intro Session (Gaza Sky Geeks)

![Gaza Sky Geeks Logo](GSG_Logo.jpg)

This repository is a fork of the **ReAct Agent example** used during the  
**AI Agents Introductory Session** delivered by Scott Johnson (AI Engineer at Workday)  
as part of the Gaza Sky Geeks training program.

The session introduced the fundamentals of AI Agents, how LLMs interact with tools,  
and how ReAct (Reasoning + Acting) enables an LLM to plan, take actions, observe results,  
and produce final answers.

This repository contains the example code used in the workshop, along with tools, prompts,  
and agent logic for experimentation and learning.

---

## 📁 Repository Structure

| File / Folder     | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `agent.py`        | Main ReAct agent implementation using LangChain and Ollama                  |
| `tools.py`        | Collection of tools (calculator, geocode, weather, file operations, etc.)   |
| `utils.py`        | Helper functions for API requests                                           |
| `requirements.txt`| Python dependencies for running the agent                                   |
| `.gitignore`      | Git ignore rules                                                            |
| `docs/` (optional)| Folder containing session materials such as the PDF                         |

---

## 🧠 Topics Covered in the Session

- What is an LLM and how it behaves  
- What LLMs **cannot** do without tools  
- What is an **AI Agent** (LLM + Tools + Loop)  
- ReAct framework (Thought → Action → Observation → Final Answer)  
- Building a simple ReAct agent with LangChain  
- Adding tools to an agent  
- Using Ollama to run local LLMs  
- Subagents and planning tools  
- Evaluating agents using LLM-as-a-judge  

---

## 🛠 Tools Included

- **calculator** – evaluate math expressions  
- **random_int** – generate random numbers  
- **geocode** – get city coordinates  
- **weather** – fetch weather data  
- **time** – get time in a timezone  
- **ls / read / write** – file operations  
- **wikipedia** – fetch summaries from Wikipedia  

---

## 🚀 How This Repo Was Used

This repository was cloned during the workshop to demonstrate:

- Running a local LLM with Ollama  
- Executing a ReAct agent  
- Observing the reasoning/action loop  
- Modifying tools and prompts  
- Experimenting with different models  

Although Ollama is required to run the agent, the code remains a valuable reference  
for understanding agent architecture and tool integration.

---

## 📄 Session Materials (PDF)

This repository includes the **AI Agents Intro Session PDF**, which contains  
the slides and explanations used by the instructor during the workshop.

You can find it inside the `docs/` folder after uploading it.

> **Note:** The PDF is included for educational and documentation purposes only.

---

## 👩‍💻 Author (Documentation)

**Deema Mohammed AL-Maqadma**  
Computer Science Student | GSG Trainee  
Interested in AI, agents, and practical applications of LLMs.

---

## 📝 Notes

- This is a fork for learning and documentation purposes.  
- The original repository belongs to **scottdjohnson**.  
- Ollama is required to run the agent locally.
