# Agentic engineering workflow

This repository contains my agentic engineering workflow. I'm using this as my personal set of skills and agents to help
me engineering high quality solutions for Info Support and my personal projects. It's suitable for a team-level approach
to agentic engineering.

## Core principles

- **Human understanding before agent execution.** It's important to be able to review and understand what you're building. Agent execution speed is second to this.

- **Progressive elaboration.** Detail is added just-in-time, not upfront. High-level decisions land before low-level ones. Agents can explore information from a hierarchical perspective.

- **Outcome over output.** Stories and features are output-based; epics are outcome-based.

## Installation

This repository is a claude plugin and can be installed easily into any agent using `npx skills install https://github.com/wmeints/agentic-engineering-workflow`.

## What is included

The skills in this repository are spread across 4 key concerns in a software project:

1. **Architecture:** Includes support for creating architecture documentation following the [Arc42](https://docs.arc42.org) standard. Also includes support for recording architecture decisions so your agents are better at following structure.

2. **Functional decomposition:** Includes how to set up a backlog with epics, features, and stories. Also includes skills and descriptions to help your agent understand how to implement stories effectively.

3. **UX and design system:** Includes how to create a design system for your application and how to translate this system into UX guidance for your agent.

5. **Testing strategy:** Includes how to set a testing strategy and how to support your agent build acceptance tests, integration tests, and unit testse. 

## Documentation

To help you get the most out of this workflow, I've included documentation as markdown.
Please find the following docs here:

- [Architecture](docs/architecture/README.md)
- [Functional decomposition](docs/functional-decomposition/README.md)
- [User Experience](docs/user-experience/README.md)
- [Testing](docs/testing/README.md)