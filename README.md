# Snapshots Directory

This directory contains snapshots of your Language Server Protocol (LSP) code for AI interactions. Each snapshot is a markdown file that includes relevant code context and project structure information, capturing the state of your workspace at the time of the AI interaction.

## What's included in snapshots?

- Selected code files and their contents
- Current file context and selections
- Project structure information (if enabled)
- Your prompt/question for the AI
- Workspace folder structure
- Environment information

## Purpose

Snapshots help maintain a record of AI interactions and provide context for future reference. They can be useful for:

- Tracking changes suggested by AI
- Referencing past solutions
- Sharing context with team members
- Documenting your development process
- Preserving LSP specification and implementation details during development

## Configuration

You can customize snapshot behavior in `config.json`. Some configurable options include:

- Enabling/disabling snapshots
- Controlling the amount of context included
- Setting retention policies
- Specifying directories to include or exclude

## Note

Snapshots do not automatically sync with your code changes. If you modify files after creating a snapshot, the snapshot will still reflect the state at the time it was created.

For questions about this repository's Language Server Protocol implementation or specifications, please refer to the main documentation.
