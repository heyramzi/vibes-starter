# Project Name

## Overview
Brief description of what this project does and its purpose.

## Structure
Key directories and files in the project:
- `/src`: Core source code
- `/docs`: Documentation
- `/tests`: Test files

## Technologies
- Main language: 
- Frameworks:
- Key libraries:

## Setup
Installation and configuration steps.

## Usage
How to use the project with simple examples.

## Development
Guidelines for contributing to the project.

## Architecture
Brief description of the system design.


This template is intended at helping users use Cursor

You can remove this section and update the readme with your actual project details

# How to use this project:

## Files Purpose

This project contains several key files and directories:

* **README.md**: Project documentation with setup instructions and overview
* **.doc/handoff/feature-handoff.md**: Template for creating structured handoff documents between team members
* **changelog.md**: Record of all notable changes to the project organized by version
* **PRD.md**: Product Requirements Document template for defining project specifications
* **.cursorrules.md**: Clean code principles and best practices for development
* **/src**: Directory containing the core source code of the application

These files provide structure and documentation to help maintain code quality and facilitate collaboration.

## System Prompt Template
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