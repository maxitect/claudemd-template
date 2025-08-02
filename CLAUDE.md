# Project: [Project Name]

## Project Overview

A brief description of the project, its purpose, and key goals.

## Tech Stack

- Languages: [list primary languages]
- Frameworks: [list frameworks]
- Tools: [list tools]

## Code Style & Conventions

- Import standards
- Code formatting guidelines
- Naming conventions
- Project-specific patterns to follow

## Development Workflow

- Branch strategy
- Commit message format
- PR requirements

## Testing Strategy

- Test frameworks
- Coverage requirements
- Test naming conventions

## Environment Setup

- Required environment variables
- Setup commands
- Local development server

## Common Commands

```bash
# Build command
[command]

# Test command
[command]

# Lint command
[command]

# Check command
[command]

# Development server
[command]
```

## Project Structure

Key directories and their purpose:

- `/src` - [description]
- `/tests` - [description]
- [other important directories]

## Post-Implementation Process

### Review Process Guidelines

Before submitting any code, ensure the following steps are completed:

1. - **Check that code, file names and comments use British spelling** - ie standardise not standardize

2. **Run all lint, check and test commands**

3. **Review outputs and iterate until all issues are resolved**

4. **Assess compliance**:
   For each standard, explicitly state ✅ or ❌ and explain why:

   - Code style and formatting
   - Naming conventions
   - Architecture patterns
   - Error handling
   - Test coverage
   - Documentation

5. **Self-review checklist**:
   - [ ] Code follows defined patterns
   - [ ] No debug/commented code
   - [ ] Error handling implemented
   - [ ] Tests written and passing
   - [ ] Documentation updated

### Documentation Updates

1. **Mark the task as done in `PLAN.md`**
2. **If the implementation touched other tasks or was unusual** - update the task itself or other tasks as relevant, note any important decisions if applicable (OPTIONAL)
3. **If applicable, update `CLAUDE.md`** with any learned standards or patterns picked up from the review process - these must be abstracted into concise documentation (OPTIONAL)
4. If there have been significant changes, update `REQUIREMENTS.md` or `ARCHITECTURE.md` as required (OPTIONAL)

**IMPORTANT**: Be concise, don't repeat yourself, double check and remove duplication/reduce where possible

### Version Control

1. **Format code before commiting** - run command `pnpm format`
2. **Commit with descriptive message**:

- **Use British spelling** - ie standardise not standardize
- **Granular commits** - do not commit all in single commit, break them up for optimal traceability
- **Informative and concise commits** - multiline is encouraged but try to keep it less than 3 lines
- **Follow commit guidance** outlined above
- **You may use gh cli** - it is installed and functioning

## Known Issues & Workarounds

Document any current limitations or workarounds Claude should be aware of.

## References

Links to relevant external documentation, design docs, or resources.
