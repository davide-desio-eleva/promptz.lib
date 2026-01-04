# Contributing to Promptz.lib

Welcome to the Promptz.lib community! This library makes it easy to share your AI development resources with the community. Simply drop your raw Kiro files and create a pull request.

## What is Promptz.lib?

Promptz.lib is a community-driven library that accepts raw Kiro files from your `.kiro` folders. These are the same files you use locally with Kiro, Kiro CLI, and Amazon Q Developer.

## What You Can Contribute

### From Your Global Kiro Folder (`~/.kiro/`)
Your user-wide configurations that work across all projects:

- **Steering Documents** (`~/.kiro/steering/*.md`) - Personal coding standards and development guidelines
- **Agent Hooks** (`~/.kiro/hooks/*.hook`) - IDE automation JSON configurations for cross-project use
- **Custom Agents** (if you have them) - Personal AI assistant configurations

### From Your Workspace Kiro Folders (`<project>/.kiro/`)
Project-specific configurations that could benefit other projects:

- **Project-specific steering** - Standards for particular frameworks or domains
- **Specialized hooks** - Project automation that others might find useful
- **Domain agents** - AI assistants for specific types of projects
- **Kiro Powers** - Complete power bundles you've created

### From Your Prompt Collections
Reusable AI instructions you've created:

- **Development prompts** - AI instructions for code generation, testing, documentation
- **Workflow prompts** - Task-specific AI guidance for common development activities
- **Domain-specific prompts** - Specialized instructions for particular technologies or frameworks

### From Your Power Collections
If you've created Kiro powers, you can contribute the complete power structure:

- **Power bundles** - Complete directories with POWER.md, optional mcp.json, and steering files

## File Structure Examples

### Steering Documents
```
steering/
├── nextjs-standards.md          # Next.js development guidelines
├── typescript-conventions.md   # TypeScript coding standards
├── security-practices.md       # Security best practices
└── testing-guidelines.md       # Testing standards
```

### Agent Hooks (JSON .hook files)
```
hooks/
├── auto-format-on-save.hook     # JSON configuration for formatting on save
├── run-tests-on-commit.hook     # JSON configuration for pre-commit testing
└── update-docs-on-change.hook   # JSON configuration for doc updates
```

### Custom Agents
```
agents/
├── code-reviewer/
│   ├── config.json          # Agent configuration with mcpServers, tools, etc.
│   └── agent.md             # Optional system prompt/instructions
├── documentation-writer/
│   ├── config.json
│   └── agent.md
└── test-generator/
    ├── config.json
    └── agent.md
```

### Kiro Powers
```
powers/
├── api-testing-suite/
│   ├── POWER.md             # Main power file with frontmatter and instructions
│   ├── mcp.json             # Optional MCP server configuration
│   └── steering/            # Optional additional steering files
│       ├── getting-started.md
│       └── best-practices.md
└── database-migration-helper/
    ├── POWER.md
    ├── mcp.json
    └── steering/
        └── troubleshooting.md
```

## How to Contribute

### For Beginners

1. **Find your Kiro files:**
   - **Global files**: Look in your home directory at `~/.kiro/`
   - **Project files**: Look in your project directories at `<project>/.kiro/`

2. **Choose what to share:**
   - Start with steering documents or prompts you find most useful
   - Consider what would help other developers in similar situations

3. **Fork and add:**
   - Fork this repository on GitHub
   - Copy your files to the appropriate directories (steering/, prompts/, hooks/, agents/, powers/)
   - Keep the same file names and structure

4. **Create a pull request:**
   - Add a clear title describing what you're contributing
   - Explain how others might use your contribution

### For Experienced Kiro Users

1. **Audit your `.kiro` folders:**
   ```bash
   # Check your global Kiro configuration
   ls -la ~/.kiro/
   
   # Check project-specific configurations
   find . -name ".kiro" -type d
   ```

2. **Select valuable contributions:**
   - Steering documents with broad applicability
   - Prompts that solve common development challenges
   - Hooks that automate frequent tasks
   - Agents that provide specialized assistance
   - Powers that package complete workflows

3. **Prepare for contribution:**
   - Remove any sensitive information (API keys, personal data)
   - Ensure file paths and references work for others
   - Test that your configurations work in clean environments

4. **Contribute systematically:**
   - Group related files in a single PR
   - Provide context about when and how to use your contributions
   - Include any dependencies or setup requirements

## Content Guidelines

### File Requirements
- **No sensitive data** - Remove API keys, passwords, personal information
- **Generic paths** - Use relative paths or placeholders instead of absolute paths
- **Clear naming** - Use descriptive file names that explain the purpose
- **Proper formatting** - Follow markdown standards for .md files

### Frontmatter for Markdown Files
Include metadata at the top of your markdown files:

```yaml
---
title: "Descriptive Title"
description: "Brief explanation of what this does"
author: "Your Name"
categories: ["category1", "category2"]
keywords: ["keyword1", "keyword2", "keyword3"]
---

Your content here...
```

### Configuration Files
For `.hook` files (JSON documents) and agent configurations, ensure:
- All referenced tools and commands are commonly available
- Paths are relative or use environment variables
- Dependencies are clearly documented
- JSON syntax is valid and properly formatted

### Hook Files (.hook)
Hook files are JSON documents stored in `.kiro/hooks/` that define automation triggers:
- Use valid JSON syntax
- Include clear trigger conditions
- Specify file patterns accurately
- Test hook behavior before contributing

## Quality Standards

### Before Contributing
- **Test your files** - Ensure they work in a clean Kiro environment
- **Remove personal data** - Strip out any sensitive or personal information
- **Check compatibility** - Verify files work with current Kiro versions
- **Document usage** - Include clear instructions or examples

### What We Look For
- **Broad applicability** - Contributions that help many developers
- **Clear documentation** - Well-explained purpose and usage
- **Working examples** - Tested and functional configurations
- **Community value** - Resources that solve real development challenges

## Getting Help

- **Questions?** Open a GitHub issue with the "question" label
- **Problems?** Report bugs with the "bug" label  
- **Ideas?** Share feature requests with the "enhancement" label

## Review Process

1. **Automated checks** - Files are validated for format and safety
2. **Community review** - Other contributors may provide feedback
3. **Maintainer approval** - Final review for quality and appropriateness
4. **Merge and publish** - Approved contributions appear on promptz.dev automatically

## Recognition

Contributors are automatically credited through git history and displayed on promptz.dev with:
- Author attribution on all contributed content
- Contributor profiles showing your contributions
- Community recognition for valuable resources

---

Thank you for sharing your Kiro configurations with the community! Your contributions help make AI-assisted development more accessible and effective for everyone. 🚀