# Promptz.lib - Community AI Development Resources

[![Community Driven](https://img.shields.io/badge/community-driven-brightgreen.svg)](https://github.com/cremich/promptz.lib)
[![Kiro Compatible](https://img.shields.io/badge/kiro-compatible-blue.svg)](https://kiro.dev)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

Welcome to promptz.lib - the community-driven library for AI-assisted development resources for Kiro! This repository contains a curated collection of prompts, steering documents, agent hooks, custom agents, and Kiro powers shared by developers worldwide.

## 🚀 What is Promptz.lib?

Promptz.lib is a community repository that accepts **raw Kiro files** from your `.kiro` folders. These are the same files you use locally with Kiro, Kiro CLI, and Amazon Q Developer. By sharing your configurations, you help other developers accelerate their AI-assisted development workflows.

## 📁 Repository Structure

```
promptz.lib/
├── agents/           # Custom AI agents with configurations
├── hooks/            # IDE automation hooks (.hook JSON files)
├── powers/           # Kiro power bundles
├── prompts/          # Reusable AI instructions
├── steering/         # Development standards and guidelines
├── CONTRIBUTING.md   # Detailed contribution guidelines
└── README.md         # This file
```

## 🎯 Content Types

### Steering Documents
Development standards and coding guidelines that ensure AI assistants follow established patterns.

**Examples:**
- Framework-specific standards (Next.js, React, TypeScript)
- Security best practices
- Testing guidelines
- Code review standards

### Prompts
Reusable AI instructions for specific development tasks.

**Examples:**
- Code generation prompts
- Documentation generators
- Test creation instructions
- Refactoring guidance

### Agent Hooks
JSON configuration files (`.hook`) that automate development workflows by executing predefined actions on IDE events.

**Examples:**
- Auto-format on file save
- Run tests before commit
- Update documentation on code changes
- Security scanning triggers

### Custom Agents
Specialized AI assistants configured for specific workflows and development processes.

**Examples:**
- Code review agents
- Documentation writers
- Test generators
- Architecture advisors

### Kiro Powers
Complete power bundles with `POWER.md`, optional `mcp.json`, and steering files that package tools, workflows, and best practices.

**Examples:**
- API testing suites
- Database migration helpers
- Cloud infrastructure managers
- Monitoring and observability tools

## 🤝 How to Contribute

Contributing to Promptz.lib is simple - just share your raw Kiro files!

### Quick Start

1. **Fork this repository**
2. **Find your Kiro files:**
   - Global: `~/.kiro/` (user-wide configurations)
   - Project-specific: `<project>/.kiro/` (project configurations)
3. **Copy your files** to the appropriate directories
4. **Remove sensitive data** (API keys, passwords, personal paths)
5. **Create a pull request**

### What to Share

Share configurations that would help other developers:
- Steering documents with broad applicability
- Prompts that solve common development challenges
- Hooks that automate frequent tasks
- Agents that provide specialized assistance
- Powers that package complete workflows

### Before Contributing

- ✅ Remove any sensitive information (API keys, passwords, personal data)
- ✅ Ensure file paths work for others (use relative paths or placeholders)
- ✅ Test your configurations in clean environments
- ✅ Add clear descriptions and usage instructions

For detailed guidelines, see [CONTRIBUTING.md](CONTRIBUTING.md).

## 🔍 How to Use These Resources

### For Kiro IDE Users

1. **Browse the repository** to find relevant resources
2. **Copy files to your `.kiro` folders:**
   - Global configurations: `~/.kiro/`
   - Project-specific: `<project>/.kiro/`
3. **Restart Kiro** to load new configurations
4. **Customize as needed** for your specific use case

### For Kiro CLI Users

1. **Download relevant files** from the repository
2. **Place in appropriate directories** based on your needs
3. **Update configurations** to match your environment
4. **Test functionality** before relying on automation

### Integration with Promptz.dev

All content in this repository is automatically processed and displayed on [promptz.dev](https://promptz.dev), where you can:
- **Search and discover** resources across all content types
- **View detailed information** including author attribution and git history
- **Access direct links** to source files and documentation

## 🏆 Community Recognition

Contributors are automatically recognized through **Author attribution** on all contributed content.

## 📊 Repository Stats

This repository contains resources from developers worldwide, helping accelerate AI-assisted development for the entire community.

## 🤔 Getting Help

- **Questions?** Open a GitHub issue with the "question" label
- **Problems?** Report bugs with the "bug" label
- **Ideas?** Share feature requests with the "enhancement" label
- **Discussions** Use GitHub discussions for community conversations

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Contributors** - Thank you to all developers sharing their Kiro configurations
- **Kiro Team** - For creating the amazing AI-assisted development platform
- **Community** - For making AI development more accessible and collaborative

---

**Ready to contribute?** Check out our [CONTRIBUTING.md](CONTRIBUTING.md) guide and start sharing your AI development resources with the community!

**Explore the collection:** Visit [promptz.dev](https://promptz.dev) to browse and search all available resources.
