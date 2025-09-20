# GitHub Copilot Guide

## 1. Chat Overview

### How does it work?

GitHub Copilot Chat provides an interactive interface where you can communicate with AI to get coding assistance, explanations, and solutions.

#### Key Components
- **Introduction**: Getting started with Copilot Chat
- **Chat window**: Interactive communication interface
- **New chat**: Start fresh conversations
- **History**: Access previous chat sessions
- **Settings**: Customize your Copilot experience
- **Model Selection**: Choose between different AI models (e.g., GPT, Gemini, Claude, etc.)
- **Voice Input**: Use voice commands to interact with Copilot (if supported)

**Reference**: https://code.visualstudio.com/docs/copilot/chat/copilot-chat

### Modes of Interaction

- **Ask**: You can ask questions directly to Copilot in the chat interface  
  **Reference**: https://code.visualstudio.com/docs/copilot/chat/chat-ask-mode
- **Edit**: If you don't like the initial suggestion, you can edit or refine the response  
  **Reference**: https://code.visualstudio.com/docs/copilot/chat/copilot-edits
- **Agent**: Copilot can act as an AI agent, ready to help you with coding tasks, generating code, answering questions, and more
  - Accept and undo the changes
  - Reverting checkpoints
  
  **Reference**: https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode


### Tools Available

Copilot integrates a range of helpful tools to enhance productivity:

- **Vision Support**: Get assistance with visual-related coding tasks
  - *Example*: Analyze UI mockups and generate corresponding code
  - ![Sample UI](images/sample_ui.png)
- **Web Search**: Search the web for relevant code examples or solutions (Note: Limited by model's knowledge cutoff)
  - *Example*: Setting up a latest tailwind css setup
- **MCP Servers**: Manage and interact with your development environment
  - MCP markets
  - Custom MCP integration
  - List MCP and MCP integrations
  
  **Reference**: https://docs.github.com/en/copilot/how-tos/provide-context/use-mcp
  - *Example*: Connect to databases, external services, or development tools
- **Source Control**: Integrated with version control systems, Copilot helps track changes and manage code
  - *Example*: Generate commit messages, review diffs, and suggest improvements
- **Custom Instructions**: Access via Copilot Settings or Command Palette → "New instructions file"  
  **Reference**: https://docs.github.com/en/copilot/how-tos/configure-custom-instructions
---

## 2. Auto Completion (Ghost Text)

### What is it?

GitHub Copilot can automatically complete your code as you type, providing suggestions right in your editor. This feature helps speed up coding by offering relevant code snippets.

### How does it work?

**Setup**: Enable ghost text in VS Code settings (accessible via the settings icon in the bottom left corner)

#### Keyboard Shortcuts
- **Ctrl + Right Arrow**: Moves through the ghost text suggestions, line by line, to complete your code
- **Alt + \\**: Manually trigger Copilot's suggestions

#### Best Practices
- **Comment First**: For the best auto-completion results, comment your requirements before you start coding. Copilot uses those comments to generate more accurate code
- **Next Edit Suggestion**: Copilot can suggest the next logical piece of code you might need, making coding more intuitive *(may need to be enabled)*

---

## 3. Inline Code Generation

### How does it work?

#### Primary Command
- **Ctrl + I**: Triggers Copilot to generate inline code based on the context of what you're working on

#### Advanced Commands
- **`/doc`**: Request Copilot to generate documentation
- **`/test`**: Ask Copilot to create unit tests
- **`/explain`**: Have Copilot explain code or logic in simple terms

---

## 4. Advanced Features

### Code Reviewer
- **Within the IDE**: Access via Command Palette → "Code Review"
- **On GitHub**: Integrated code review assistance
- **Benefits**: Copilot can assist in reviewing your code for best practices, consistency, and improvements

### PR (Pull Request) Reviewer
- **IDE Integration**: Available on the source control tab
- **GitHub Integration**: Direct PR review assistance
- **Quality Assurance**: Ensures your PRs align with standards and improves code quality


**Reference**: https://docs.github.com/en/copilot/how-tos/use-copilot-agents/request-a-code-review/configure-automatic-review

### Commit Message Generator
Automatically generates meaningful commit messages based on your code changes.

### Copilot Coding Agent

The Copilot Coding Agent can work autonomously in the background, much like a human developer completing tasks. The agent is tracked via the **Agent Panel** and can perform the following tasks:

#### Core Capabilities
- **Fix Bugs**: Copilot can automatically identify and fix bugs
- **Implement Features**: Work on incremental features, making updates or adjustments as needed
- **Improve Test Coverage**: Ensure that your code is well-tested by generating additional tests
- **Update Documentation**: Helps maintain and update documentation to reflect your latest code changes
- **Address Technical Debt**: Assists with refactoring code to make it cleaner and more efficient

### Workspace and Code Space Index
- **Seamless Integration**: Copilot integrates into your workspace, indexing your code for faster, more context-aware suggestions
- **Navigation**: Helps navigate through your codebase with ease
- **Context Awareness**: Provides suggestions based on your entire project structure

### Adding Custom Instructions to Your Repository
You can personalize Copilot's behavior by adding custom instructions directly to your repository, ensuring that it adapts to your project's specific needs and coding standards.

**Reference**: https://docs.github.com/en/copilot/how-tos/use-copilot-agents/coding-agent
---

## 🎯 Quick Reference

### Essential Shortcuts
| Action | Shortcut | Description |
|--------|----------|-------------|
| Auto Complete | `Ctrl + Right Arrow` | Accept ghost text suggestions |
| Manual Trigger | `Alt + \` | Manually trigger Copilot |
| Inline Generation | `Ctrl + I` | Generate code inline |

### Chat Commands
| Command | Purpose |
|---------|---------|
| `/doc` | Generate documentation |
| `/test` | Create unit tests |
| `/explain` | Explain code logic |

### Tips for Better Results
1. **Write clear comments** describing what you want to achieve
2. **Provide context** in your variable and function names
3. **Use consistent coding patterns** in your project
4. **Review suggestions** before accepting them
5. **Customize instructions** for your specific project needs
