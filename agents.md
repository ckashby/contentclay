# AI Coding Agents Configuration

This file provides instructions and context for AI coding assistants working on this project. It is designed to be compatible with multiple AI tools including Claude Code, Cursor, GitHub Copilot, and others.

## Project Overview

<!-- Describe your project here -->
- **Project Name**: [Project Name]
- **Description**: [Brief description of what the project does]
- **Tech Stack**: [List main technologies, frameworks, and languages]

## Project Structure

<!-- Update this section to reflect your actual project structure -->
```
project-root/
├── src/           # Source code
├── tests/         # Test files
├── docs/          # Documentation
├── config/        # Configuration files
└── scripts/       # Build and utility scripts
```

## Coding Standards

### General Principles
- Write clean, readable, and maintainable code
- Follow DRY (Don't Repeat Yourself) principles
- Use meaningful variable and function names
- Keep functions small and focused on a single responsibility
- Write self-documenting code with comments only where necessary

### Code Style
<!-- Customize these for your project -->
- **Indentation**: 2 spaces (or 4 spaces, or tabs)
- **Line Length**: Maximum 100 characters
- **Naming Conventions**:
  - Variables: `camelCase` or `snake_case`
  - Constants: `UPPER_SNAKE_CASE`
  - Classes/Types: `PascalCase`
  - Files: `kebab-case` or `PascalCase`

### Documentation
- Document public APIs and complex logic
- Keep README files up to date
- Use inline comments sparingly and meaningfully

## Testing Guidelines

- Write tests for new features and bug fixes
- Maintain good test coverage
- Follow the testing patterns established in the project
- Use descriptive test names that explain the expected behavior

## Git Commit Guidelines

- Write clear, descriptive commit messages
- Use conventional commits format when applicable:
  - `feat:` for new features
  - `fix:` for bug fixes
  - `docs:` for documentation changes
  - `refactor:` for code refactoring
  - `test:` for test changes
  - `chore:` for maintenance tasks

## AI Assistant Instructions

### Context Awareness
- Read existing code before making changes to understand patterns and conventions
- Check for existing utilities or helpers before creating new ones
- Maintain consistency with the existing codebase style

### Code Generation
- Generate code that follows the project's established patterns
- Include appropriate error handling
- Consider edge cases in implementations
- Add necessary imports and dependencies

### Communication
- Explain significant changes or decisions
- Ask clarifying questions when requirements are ambiguous
- Provide context for suggested changes

### Safety and Quality
- Do not introduce security vulnerabilities
- Validate inputs and handle errors appropriately
- Consider performance implications
- Ensure backward compatibility when modifying existing code

## Tool-Specific Configurations

### Claude Code (CLAUDE.md)
This file serves as the CLAUDE.md configuration. For Claude-specific instructions, you can also create a separate `CLAUDE.md` file in the project root.

### Cursor (.cursorrules)
To use these instructions with Cursor, create a `.cursorrules` file with:
```
# Include this file
@agents.md
```

Or copy the relevant sections directly into `.cursorrules`.

### GitHub Copilot
GitHub Copilot will automatically consider this file when providing suggestions. You can also add a `.github/copilot-instructions.md` file for Copilot-specific instructions.

### Other AI Tools
Most AI coding assistants will recognize and use this file when present in the project root. Adjust as needed for your specific tool.

## Customization

### Adding Project-Specific Instructions
Add sections below for project-specific guidelines:

<!-- Example custom sections:
### API Guidelines
- REST API endpoints should follow our naming conventions
- All endpoints must have proper authentication
- Return appropriate HTTP status codes

### Database Guidelines
- Use migrations for schema changes
- Index frequently queried columns
- Follow naming conventions for tables and columns
-->

### Environment Setup
<!-- Add setup instructions for new developers/AI assistants -->
1. [Step 1]
2. [Step 2]
3. [Step 3]

### Common Tasks
<!-- Document common development tasks -->
- **Running the application**: `[command]`
- **Running tests**: `[command]`
- **Building for production**: `[command]`
- **Linting**: `[command]`

---

*Last updated: [Date]*
*Update this file as your project evolves and conventions change.*
