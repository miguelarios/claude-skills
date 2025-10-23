# Claude Skills

A curated collection of custom skills for [claude.ai](https://claude.ai), shared publicly to help the community extend Claude's capabilities.

## What are Claude Skills?

Claude Skills are reusable, specialized capabilities that enhance Claude's functionality on claude.ai. Each skill is a folder containing a `SKILL.md` file with instructions (in YAML frontmatter and markdown) plus optional supporting files like scripts and templates. Claude automatically invokes relevant skills based on your requests - no manual selection needed!

Skills are available for Pro, Max, Team, and Enterprise users.

## How to Use These Skills

### Skill Structure

Each skill in this repository is organized as a folder containing:
- `SKILL.md` - The main skill file with YAML frontmatter and instructions
- Optional supporting files (scripts, templates, etc.)

### Installing a Skill

1. Download the skill folder you want from this repository
2. Create a ZIP file of the skill folder
3. Go to [claude.ai](https://claude.ai) and navigate to Settings
4. Click on "Capabilities" in the left sidebar
5. Find the "Skills" section and click "Upload skill"
6. Upload your ZIP file
7. Enable the skill

### Using a Skill

Once installed and enabled, skills work automatically! Claude will invoke the appropriate skill based on your conversation context and the skill's description. Simply work naturally - if your request matches a skill's purpose, Claude will use it automatically.

For example, if you have a presentation skill installed and ask "Create a PowerPoint about Q3 results," Claude will automatically use that skill.

## Available Skills

*Skills will be added here as they are developed and published.*

<!--
Example format for listing skills:

### skill-name
**Description**: Brief description of what the skill does
**Use Case**: When Claude will automatically invoke this skill
**Files**: List of key files included in the skill
-->

## Contributing

This is a personal collection, but suggestions and contributions are welcome! If you have ideas for improvements or find issues:

1. Open an issue describing your suggestion or the problem
2. For contributions, fork the repository and submit a pull request
3. Ensure your skills are well-documented and follow best practices

## Skill Development Guidelines

When creating skills for this collection:

- **Clear Purpose**: Each skill should have a well-defined, specific purpose
- **SKILL.md Format**: Every skill must include a `SKILL.md` file with:
  - YAML frontmatter with metadata (name, description, etc.)
  - Clear instructions for Claude in markdown format
- **Folder Structure**: Organize each skill in its own folder with all necessary files
- **Documentation**: Include clear documentation about what the skill does and when it's invoked
- **Testing**: Test skills thoroughly before sharing
- **Naming**: Use descriptive, kebab-case folder names (e.g., `presentation-creator`, `code-analyzer`)

### Example SKILL.md Structure

```markdown
---
name: skill-name
description: Brief description of what this skill does
---

# Skill Instructions

[Instructions for Claude about how to use this skill]
```

## Resources

- [Claude.ai](https://claude.ai)
- [Official Anthropic Skills Repository](https://github.com/anthropics/skills) - Examples and templates
- [Using Skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude) - Official support article
- [Claude Skills Announcement](https://www.anthropic.com/news/skills) - Introduction to skills
- [Anthropic Documentation](https://docs.anthropic.com)

## License

[Specify your license here - e.g., MIT, Apache 2.0, etc.]

## Contact

For questions or feedback, please open an issue in this repository.
