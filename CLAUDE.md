# Claude Code Demo Project

## Project Overview
This project creates a Quarto presentation about working with Claude Code, designed for deployment as GitHub Pages. The presentation follows Jeremy Howard's dialogue engineering approach from Answer.AI - working interactively in small steps rather than large code dumps.

## Working Philosophy
We follow the **dialogue engineering** methodology:
- Work in small, iterative steps
- Continuous feedback between human and AI
- Each step makes both human and AI smarter
- Focus on collaborative refinement over one-way generation

## Project Structure
- `claude-code.qmd` - Main Quarto markdown file for presentation
- `_quarto.yml` - Quarto configuration for GitHub Pages
- `styles.css` - Custom styling for the presentation
- `CLAUDE.md` - This file (project instructions)
- `pyproject.toml` - uv project configuration

## Development Workflow
1. **Plan interactively** - Break tasks into small steps
2. **Implement incrementally** - Build one slide/section at a time
3. **Test frequently** - Preview changes after each step
4. **Iterate based on feedback** - Refine content and approach

## Development Environment
- **Python Environment**: uv for virtual environment management
- **Quarto**: Installed via Homebrew (has non-Python dependencies)
- **Quarto Markdown**: Visual Studio Code (Claude Code has access)
- **Version Control**: Git with GitHub Pages deployment

## Key Commands
```bash
# Set up Python environment (if needed for code execution)
uv add jupyter

# Preview presentation locally (Quarto via Homebrew)
quarto preview claude-code.qmd

# Render presentation
quarto render claude-code.qmd

# Publish to GitHub Pages
quarto publish gh-pages
```

## Content Focus
The presentation covers:
- Introduction to Claude Code and dialogue engineering
- Interactive development principles
- Practical examples and live demos
- Best practices for AI-assisted coding
- Step-by-step problem-solving approaches

## Deployment
- Target: GitHub Pages
- Format: Quarto RevealJS presentation
- Theme: Dark mode for better presentation visibility
- Features: Interactive slides, code examples, live demos