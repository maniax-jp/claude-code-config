# Guidelines

This document defines the project's rules, objectives, and progress management methods. Please proceed with the project according to the following content.

## Top-Level Rules

- **You must think exclusively in English**. However, you are required to **respond in Japanese**. Also code comments, commit messages and documentation should be written in Japanese.
- To understand how to use a library, **always use the Contex7 MCP** to retrieve the latest information.
- For temporary notes for design, create a markdown in `.tmp` and save it.
- **After using Write or Edit tools, ALWAYS verify the actual file contents using the Read tool**, regardless of what the system-reminder says. The system-reminder may incorrectly show "(no content)" even when the file has been successfully written.
- Please respond critically and without pandering to my opinions, but please don't be forceful in your criticism.

## Programming Rules

- Avoid hard-coding values unless absolutely necessary.

## Development Style

### Overview

When receiving development tasks, please follow the 5-stage workflow below. This ensures requirement clarification, structured design, comprehensive testing, and efficient implementation.

### 5-Stage Workflow

#### Stage 1: Requirements

- Analyze user requests and convert them into clear functional requirements
- Document requirements in `.tmp/requirements.md`

#### Stage 2: Design

- Create technical design based on requirements
- Document design in `.tmp/design.md`

#### Stage 3: Test Design

- Create comprehensive test specification based on design
- Document test cases in `.tmp/test_design.md`

#### Stage 4: Task List

- Break down design and test cases into implementable units
- Document in `.tmp/tasks.md`

#### Stage 5: Implementation

- Implement according to task list
- For each task:
  - Update task to in_progress
  - Execute implementation and testing
  - Run lint and typecheck
  - Update task to completed

### Important Notes

- Each stage depends on the deliverables of the previous stage
- Please obtain user confirmation before proceeding to the next stage
- Always use this workflow for complex tasks or new feature development
- Simple fixes or clear bug fixes can be implemented directly

# important-instruction-reminders
Do what has been asked; nothing more, nothing less.
NEVER create files unless they're absolutely necessary for achieving your goal.
ALWAYS prefer editing an existing file to creating a new one.
NEVER proactively create documentation files (*.md) or README files directly in the project root or docs directory. Only create documentation files under the .tmp directory. Move them to the appropriate location only when explicitly instructed.
