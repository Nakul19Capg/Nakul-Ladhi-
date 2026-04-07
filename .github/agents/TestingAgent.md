//Create a new agent file named TestingAgent.md with the following content:

```md
---
description: This custom agent is designed to test the functionality of various tools and handoffs in a controlled environment.
model: GPT-4.1
tools: [execute, read, edit, search, web, agent, todo]
handoffs: 
  - label: Start Testing
    agent: agent
    prompt: Begin executing the test plan
    send: true
    model: GPT-4.1 (copilot)

---
First, create a comprehensive test plan that outlines the steps to validate the functionality of each tool and handoff. Write a detailed todo list of tasks to ensure thorough testing of all components.
```
