# Agentic engineering workflow

This repository contains my agentic engineering workflow. I'm using this as my personal set of skills and agents to help
me engineering high quality solutions for Info Support and my personal projects. It's suitable for a team-level approach
to agentic engineering.

## Core principles

- **Human understanding before agent execution.** We don't hand work to an agent until humans have a coherent picture of what to build and why. 

- **Progressive elaboration.** Detail is added just-in-time, not upfront. High-level decisions land before low-level ones.

- **Human review capacity is the bottleneck.** Sizing decisions optimize for reviewability, not for agent throughput.

- **Four peer concerns.** Functional decomposition, architecture, UX, and test strategy are first-class peers — none is subordinate to the others.

- **One artifact per concern.** Avoid duplication; cross-link rather than copy.

- **Outcome over output.** Stories and features are output-based; epics are outcome-based.

## Installation of the tools

This repository is a claude plugin and can be installed easily into any agent using `npx skills install https://github.com/wmeints/agentic-engineering-workflow`.