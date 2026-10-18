# CrewAI Multi-Agent System with Google Gemini

## Overview

This project explores the development of AI-powered multi-agent systems using the CrewAI framework and Google's Gemini large language model (LLM).

CrewAI provides a framework for organizing AI agents with different roles, goals, and responsibilities. These agents can collaborate on tasks through a coordinated workflow.

The project demonstrates the use of CrewAI with Google Gemini to explore agent creation, task management, and multi-agent execution.

## Objectives

- Understand the fundamentals of Agentic AI.
- Build AI agents using the CrewAI framework.
- Integrate Google Gemini as the language model.
- Explore agent roles, goals, and task definitions.
- Understand how multiple agents can collaborate.
- Experiment with LLM-powered task execution.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| CrewAI | Framework for building collaborative AI agents |
| Google Gemini | Large language model for AI-powered reasoning and text generation |
| Jupyter Notebook | Interactive development and experimentation |
| Google Colab | Cloud-based notebook execution environment |

## Key Concepts

### 1. AI Agents

AI agents are software components designed to perform specific tasks using an underlying language model and, where configured, tools or other capabilities.

In CrewAI, agents can be assigned roles, goals, and backstories to guide their behavior.

### 2. Tasks

Tasks define the work that an agent is expected to perform.

A task may include:
- A description of the work.
- An expected output.
- An assigned agent.
- Additional execution settings, where applicable.

### 3. Crew

A crew coordinates a group of agents and their assigned tasks.

Depending on the configuration, agents can work through a sequential or other supported execution process.

### 4. Google Gemini Integration

Google Gemini provides the language-model capabilities used by the application.

The integration allows configured CrewAI agents to use Gemini for supported language-generation and reasoning tasks.

## Project Structure

```text
Agentic-ai-/
├── README.md
└── crewai_gemini_clean.ipynb
```

The repository currently contains the CrewAI notebook at its root.

If additional agent projects are added later, the repository can be organized into separate directories.

## Getting Started

### Prerequisites

Before running the project, ensure that you have:

- Python installed, if running locally.
- Access to Google Colab or Jupyter Notebook.
- A Google Gemini API key, if required by the notebook.
- The Python dependencies used by the notebook.

### Installation

Install the dependencies required by your implementation.

For example, if your notebook uses the CrewAI package:

```bash
pip install crewai
```

Install any additional packages imported by the notebook.

If you are using Google Colab, run the appropriate installation commands in a notebook cell.

### API Configuration

If the notebook uses Google Gemini through an API key, configure the key securely.

For Google Colab, you can store the key in Colab Secrets and retrieve it from the notebook.

Alternatively, when running locally, configure an environment variable and read it from your Python code.

Never commit API keys, passwords, or other credentials to GitHub.

## How to Run

1. Open the project notebook:

   [crewai_gemini_clean.ipynb](./crewai_gemini_clean.ipynb)

2. Open it in Google Colab or Jupyter Notebook.

3. Install the required dependencies.

4. Configure the Gemini API key if the notebook requires one.

5. Run the notebook cells in order.

6. Review the outputs produced by the configured agents and tasks.

## Expected Learning Outcomes

After exploring this project, you should gain an understanding of:

- The fundamentals of Agentic AI.
- Creating and configuring AI agents.
- Defining agent roles, goals, and tasks.
- Integrating a large language model with CrewAI.
- Coordinating agent execution.
- Developing and experimenting with multi-agent workflows.

## Security Considerations

- Never publish API keys or credentials in notebooks or source files.
- Use environment variables or a secrets manager for sensitive configuration.
- Avoid committing local environment files such as `.env`.
- Review notebook outputs before publishing to ensure they do not contain sensitive information.
- Check the API provider's pricing and usage limits before running the project.

## Future Enhancements

Potential extensions to this project include:

- Adding specialized agents for different responsibilities.
- Integrating external tools and data sources.
- Exploring sequential and hierarchical agent workflows.
- Adding structured output and validation.
- Comparing different agent frameworks, such as AutoGen and PhiData.
- Improving error handling and execution monitoring.

These are possible future improvements, not claims about features already implemented.

## Author

**Yashasvi**

GitHub: [@yashasvi1914](https://github.com/yashasvi1914)

## Repository

[Agentic-ai- on GitHub](https://github.com/yashasvi1914/Agentic-ai-)
