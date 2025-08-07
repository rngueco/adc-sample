---
applyTo: "**"
---

# Copilot Instructions

## Overview

This document outlines the general development guidelines and project architecture for coding agents working on this codebase. The goal is to ensure high-quality, consistent, and maintainable contributions aligned with team standards. This document is for human editing only; machines can read this document but should not edit it.

## Project Stack

- Framework: Next.js with TypeScript
- Component Library: `@shadcn/ui`
- Styling: Tailwind CSS (utility-first approach)
- Linting: ESLint with Next.js and TypeScript recommended rules
- Component Development: Storybook
- Testing: Unit tests using React Testing Library and Jest
- Package Manager: pnpm

## Folder Structure

Most project-related code lives under the src/ folder.

- `app/` contains the pages and routes
- `components/ui/` contains `@shadcn/ui` components
- `components/` contains custom components
- `docs/` contains Storybook .mdx files
- `lib/` contains shared utility functions, hooks, and types
- `services/` contains shared services
- `stories/` contains Storybook stories

## General Coding Guidelines

### Naming Conventions

- Use PascalCase for component names, interfaces, and type aliases
- Use camelCase for variables, functions, and methods
- Use ALL_CAPS for constants

### Error Handling

- Use try/catch blocks for async operations
- Implement proper error boundaries in React components
- Always log errors with contextual information

## Other Guidelines

- Use `context7` tool to get up-to-date, version-specific documentation and code examples from any library or framework
- Use `sequentialthinking` tool to break down complex tasks into manageable steps
- When writing Linear issues, provide clear steps and acceptance criteria
