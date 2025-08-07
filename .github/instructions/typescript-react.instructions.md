---
applyTo: "**/*.ts,**/*.tsx"
description: "Guidelines for writing new code in TypeScript and React"
---
# TypeScript and React Guidelines

This document provides guidelines for writing TypeScript and React code in this project.

## TypeScript Guidelines

- Use TypeScript for all new code
- Strict type checking is enabled - avoid using `any`
- Use interfaces for complex object types, arrange properties alphabetically
- Prefer type inference where possible

## React Guidelines

- Use functional components with hooks, arrange props alphabetically
- Use TypeScript generics for reusable components
- Implement error boundaries for component error handling

## ESLint

- Follow the base ESLint configuration (`next/core-web-vitals` and `next/typescript`)
- Fix all linting errors before committing

## Tailwind CSS

- Use semantic class names (text-sm, bg-muted, rounded-md) and avoid hardcoded styles
- Follow the spacing scale (0.5 = 2px, 1 = 4px, etc.)