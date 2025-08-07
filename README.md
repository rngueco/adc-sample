# AI Development Context Sample Repository

This repository serves as a practical example of implementing an AI Development Context in a software development project. It demonstrates how to effectively structure and organize AI development instructions and prompts to enhance the collaboration between developers and AI coding assistants like GitHub Copilot.

## Purpose

This project accompanies an article on Software Development in the age of AI. It showcases how to:

- Organize AI-specific instructions and prompts in a structured manner
- Implement contextual guidelines for different types of files and components
- Set up consistent development patterns that both human developers and AI assistants can follow

## Project Structure

```plaintext
.
├── .github/
│   ├── instructions/             # AI context management files
│   │   ├── components.instructions.md
│   │   ├── storybook.instructions.md
│   │   ├── test-generation.instructions.md
│   │   └── typescript-react.instructions.md
│   └── copilot-instructions.md  # Global project instructions
├── .vscode/
│   ├── mcp.json             # List of MCP servers in use
│   ├── settings.json        # Project-specific settings
│   └── ...
├── src/
│   ├── app/                 # Next.js app directory
│   ├── components/          # React components
│   │   └── ui/              # shadcn/ui components
│   ├── lib/                 # Utilities and shared code
│   └── stories/             # Storybook stories
└── ...
```

## Tech Stack

- **Framework**: Next.js with TypeScript
- **Component Library**: `@shadcn/ui`
- **Styling**: Tailwind CSS
- **Testing**: React Testing Library and Jest
- **Component Development**: Storybook
- **Package Manager**: pnpm

## AI Development Context

This repository demonstrates several key aspects of AI context management:

1. **Structured Instructions**: Organized guidelines in `.github/instructions/` for different aspects of development
2. **Pattern Matching**: Instructions are mapped to specific file patterns
3. **Global Context**: Project-wide guidelines in `copilot-instructions.md`
4. **Consistent Standards**: Clear conventions for code style, testing, and component development

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/rngueco/adc-sample.git
   ```

2. Install dependencies:

   ```bash
   pnpm install
   ```

3. Start the development server:

   ```bash
   pnpm dev
   ```

4. Open Storybook:

   ```bash
   pnpm storybook
   ```

## Contributing

This repository is meant to serve as an example. However, if you have suggestions for improving the AI Development Context structure, feel free to open an issue or submit a pull request.
