# 4oAgents

4oAgents is a Python script that leverages OpenAI's GPT-4 and Anthropic's Claude models to break down a user-provided objective into sub-tasks, execute those tasks, and refine the results into a cohesive final output. It can also generate a project folder structure and create code files based on the refined output.

## Features

- Breaks down user objectives into sub-tasks using GPT-4
- Executes sub-tasks using GPT-4 and incorporates search results from Tavily if enabled
- Refines sub-task results into a final output using Anthropic's Claude model
- Generates a project folder structure and creates code files based on the refined output
- Saves the full exchange log, including task breakdown and refined output, to a markdown file

## Requirements

- Python 3.6 or higher
- OpenAI API key
- Anthropic API key
- Tavily API key (optional, for search functionality)

## Installation

1. Clone the repository:

pip install -r requirements.txt

```bash
git clone https://github.com/sormind/4oAgents.git
