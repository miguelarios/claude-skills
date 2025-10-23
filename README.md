# Claude Skills

A curated collection of custom skills for [Claude Code](https://claude.com/claude-code), shared publicly to help the community extend Claude's capabilities.

## What are Claude Skills?

Claude Skills are reusable, specialized capabilities that extend Claude Code's functionality. They provide domain-specific knowledge and workflows that can be invoked during your coding sessions to handle complex, multi-step tasks more effectively.

## How to Use These Skills

### Installing a Skill

1. Clone this repository or download individual skill files
2. Copy the skill file(s) to your Claude Code skills directory:
   - **macOS/Linux**: `~/.config/claude-code/skills/`
   - **Windows**: `%APPDATA%\claude-code\skills\`
3. Restart Claude Code or reload your configuration

### Using a Skill

Once installed, you can invoke a skill in Claude Code by using the `@` symbol followed by the skill name:

```
@skill-name [arguments]
```

For more information about skills, visit the [Claude Code Skills documentation](https://docs.claude.com/docs/claude-code/skills).

## Available Skills

*Skills will be added here as they are developed and published.*

<!--
Example format for listing skills:

### skill-name
**Description**: Brief description of what the skill does
**Use Case**: When to use this skill
**Usage**: `@skill-name [arguments]`
-->

## Contributing

This is a personal collection, but suggestions and contributions are welcome! If you have ideas for improvements or find issues:

1. Open an issue describing your suggestion or the problem
2. For contributions, fork the repository and submit a pull request
3. Ensure your skills are well-documented and follow best practices

## Skill Development Guidelines

When creating skills for this collection:

- **Clear Purpose**: Each skill should have a well-defined, specific purpose
- **Documentation**: Include clear usage instructions and examples
- **Error Handling**: Implement proper error handling and edge cases
- **Testing**: Test skills thoroughly before sharing
- **Naming**: Use descriptive, kebab-case names (e.g., `format-json`, `generate-tests`)

## Resources

- [Claude Code Documentation](https://docs.claude.com/claude-code)
- [Skills Documentation](https://docs.claude.com/docs/claude-code/skills)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)

## License

[Specify your license here - e.g., MIT, Apache 2.0, etc.]

## Contact

For questions or feedback, please open an issue in this repository.
