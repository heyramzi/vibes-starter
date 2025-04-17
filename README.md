# Cursor Project Template

## Overview
A comprehensive starter template for projects using Cursor AI-powered IDE. This template provides structure, documentation templates, and best practices to help you build clean, maintainable code with effective AI collaboration.

## Structure
Key directories and files in this template:
- `/src`: Core source code (add your application code here)
- `/.doc`: Documentation templates and project handoff documents
- `/tests`: Add test files here (create this directory when needed)
- `README.md`: Project documentation (this file)
- `.cursorrules`: Clean code principles for AI assistance
- `PRD.md`: Product Requirements Document template
- `changelog.md`: Template for tracking project changes

## Getting Started

1. Replace this README content with your actual project details
2. Add your source code to the `/src` directory
3. Update the PRD.md with your project requirements
4. Use the feature-handoff template for collaboration
5. Track changes in the changelog.md file

## Using Cursor AI Effectively

### Feature Handoff
Use the `.doc/handoff/feature-handoff.md` template when:
- Switching between team members
- Asking Cursor AI to analyze your codebase
- Documenting components for future reference

### Clean Code Principles
The `.cursorrules` file contains best practices for:
- Naming conventions
- Code structure
- Error handling
- Performance optimization

### Product Requirements
Use the `PRD.md` template to:
- Define project scope
- Document user stories
- Set technical requirements
- Plan implementation phases

### Feature Todo Documents
The `.doc/todo/example-feature.md` serves as a template for creating structured task lists:
- Copy this template when starting new features
- Break down complex features into manageable tasks
- Track dependencies and implementation notes
- Use checkboxes to monitor progress

#### Converting Rough Requirements to Structured Todos

When you have unstructured or poorly defined requirements, use this prompt with Cursor AI to generate a structured todo document:

```
Transform these rough requirements into a structured todo document following the format in .doc/todo/example-feature.md:

[Paste your rough requirements here]

For the todo document:
1. Create a clear feature title
2. Add a concise overview of the feature's purpose
3. Break down implementation into hierarchical tasks with checkboxes
4. List all technical dependencies
5. Include relevant notes about implementation challenges or considerations
6. Make sure the tasks follow a logical implementation order
7. Keep each task focused and specific
```

This approach helps convert vague requirements like "We need user login" into comprehensive, actionable task lists organized by implementation phase.

## Recommended System Prompt for Code Analysis

```
You are a code analysis assistant tasked with creating a structured handoff document. Analyze the provided codebase and generate a clear feature handoff document following this exact structure:

For each major feature or component (limit to 5-6 features for organization):

### [Feature Name]
- **Purpose**: Write a concise description of what this feature does and its role in the application
- **Key Files**: List the most important files for this feature with brief descriptions of their responsibilities
- **Dependencies**: Identify other components, libraries, or services this feature relies on
- **Current Status**: Describe the current implementation state and any known issues
- **Improvement Areas**: Note specific aspects that need enhancement based on code quality, performance, or functionality

Focus strictly on code analysis without adding implementation suggestions. Keep descriptions factual and concise. This document will be used by another LLM agent to implement improvements.