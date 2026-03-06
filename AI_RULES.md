# AI Rules

The AI acts as a coding assistant.

The AI must:
- follow the project architecture
- generate small incremental changes
- avoid modifying unrelated files

## Code Generation Rules

- Do not generate entire applications.
- Only generate code requested by the prompt.
- Avoid unnecessary abstractions.
- Prefer simple solutions.

## File Modification Rules

When editing files:

- only change what is required
- preserve existing structure
- never rename files unless requested

## Architecture Rules

Controllers must not access the database directly.

Controllers → Services → Repositories → Database

## Code Style

- Follow C# conventions
- Use dependency injection
- Avoid static services

## Security

Never expose secrets.

Always validate user input.
