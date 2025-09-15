# LangGraph-BranchFlow

A beginner-friendly demo of **LangGraph** showing how to build branching workflows with multiple nodes and edges.
This project integrates **OpenAI** with conditional logic to handle **math vs non-math queries**, while also demonstrating preprocessing, postprocessing, and logging.
Now extended with **LangSmith Tracing** for project monitoring and debugging. 🚀

---

## ⚡ Features

- Input logging & preprocessing
- Branching flow (Math → OpenAI, Non-Math → Fun Fact)
- Postprocessing with AI note
- Final output logging
- **LangSmith integration for tracing and debugging**
- Clean and modular workflow design

---

## 🛠️ Workflow

Here’s the designed LangGraph workflow:

![Workflow](./public/Workflow.png)

---

## 📸 Example Outputs

### Math Query

`Hey, what is 2 + 2?`

![Math Output](./public/Math_Output.png)

### Non-Math Query

`Tell me a fun fact`

![Non-Math Output](./public/NonMath-Output.png)

---

## 📊 LangSmith Tracing

This project is integrated with **LangSmith** for complete visibility into node executions, branching flows, and performance.
Below are sample screenshots from LangSmith:

- **Project Overview**
  ![LangSmith Project](./public/LangSmith-Project.png)

- **Execution Calls**
  ![LangSmith Calls](./public/LangSmith-Calls.png)

- **Analytics & Charts**
  ![LangSmith Charts](./public/LangSmith-Charts.png)
