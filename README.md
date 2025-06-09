# ADK Quickstart Agent

This project contains examples of agents developed with Google Agent Development Kit (ADK). The goal is to showcase different types of agents and their capabilities:

1. **Basic Agent** - A simple agent that demonstrates the basic concepts of ADK
2. **Tool Agent** - An agent that uses built-in and custom tools to expand its capabilities
3. **Parallel Agent** - An agent that executes subtasks in parallel to improve performance and efficiency

## Disclaimer

This repository is heavily built from the [official Google ADK documentation](https://google.github.io/adk-docs/get-started/quickstart/) and the explanations from the following tutorial video:

[![Google ADK Tutorial](https://img.youtube.com/vi/P4VFL9nIaIA/0.jpg)](https://www.youtube.com/watch?v=P4VFL9nIaIA)

## Installation

```bash
# Create virtual environment
uv venv

# Activate virtual environment
source .venv/bin/activate

# Install dependencies
uv pip install -e .
```

## Dependencies

- google-adk[database] 0.3.0
- yfinance 0.2.56
- psutil 5.9.5
- litellm 1.66.3
- google-generativeai 0.8.5
- python-dotenv 1.1.0

## Documentation

For more information about ADK, see the [official Google ADK documentation](https://google.github.io/adk-docs/get-started/quickstart/).

## Project Structure

- **1-basic-agent**: Basic example of a simple conversational agent
- **2-tool-agent**: Example of an agent that uses tools
- **3-parallel-agent**: Example of an agent that executes tasks in parallel
