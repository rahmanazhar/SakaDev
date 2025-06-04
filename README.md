# SakaDev - Advanced AI Development Assistant

<div align="center">
<table>
<tbody>
<td align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=rahmanazhar.saka-dev"><strong>VS Code Marketplace</strong></a>
</td>
<td align="center">
<a href="https://docs.sakadev.online/getting-started/for-new-coders" target="_blank"><strong>Getting Started</strong></a>
<a href="https://github.com/rahmanazhar/SakaDev/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop"><strong>Request Features</strong></a>
</td>
</tbody>
</table>
</div>

Like its namesake from Malay ("Saka" meaning ghost), SakaDev works invisibly yet effectively within your development environment, moving seamlessly between files and systems to accomplish complex tasks. This AI ghost developer integrates directly with your CLI and editor, providing an ethereal presence that enhances rather than disrupts your workflow. 

Powered by [Claude 4 Sonnet's agentic capabilities](https://www.anthropic.com/claude/sonnet), it handles software development tasks with precision and reliability. Through its powerful toolset, SakaDev creates and edits files, analyzes projects, interacts with browsers, and executes terminal commands, all with a secure approval system. Going beyond code completion, it uses the Model Context Protocol (MCP) to extend its capabilities through custom tools. This combination of powerful automation and controlled oversight makes SakaDev an essential companion for professional software development.

How it works:

1. **Task Initiation**: Submit your task with optional images or screenshots to guide the process.

2. **Project Analysis**: SakaDev analyzes your codebase through:
   - File structure examination
   - Source code AST parsing
   - Targeted regex searches
   - Efficient context management

3. **Intelligent Execution**: With comprehensive project understanding, SakaDev:
   - Creates and edits files with automatic error detection and fixing
   - Executes terminal commands with real-time output monitoring
   - Performs browser-based testing and debugging when needed

4. **Task Completion**: Upon completion, SakaDev provides:
   - A summary of changes made
   - Verification steps if needed
   - One-click command execution to view results

> [!TIP]
> Use the `CMD/CTRL + Shift + P` shortcut to open the command palette and type "SakaDev: Open In New Tab" to open the extension as a tab in your editor. This lets you use SakaDev side-by-side with your file explorer, and see how he changes your workspace more clearly.

---

### Key Features

### 🤖 Use Any AI Model
Choose from a comprehensive range of AI providers:
- OpenRouter with latest models and analytics
- Claude 4 models via Anthropic, AWS, or Vertex AI
- GPT-4 series through OpenAI and Azure
- Gemini 2.5 Flash Preview with 1M token context
- Advanced models: DeepSeek R1/V3, Mistral AI, xAI Grok
- Local development with LM Studio/Ollama
- Real-time cost tracking and token monitoring

### 💻 Terminal Command Control
Execute and monitor commands with confidence:
- Direct terminal integration via VSCode shell
- Real-time output monitoring and responses
- Background process support for dev servers
- Environment-aware command execution
- Quick access via keyboard shortcuts (Cmd+')
- Granular auto-approval configuration

### 📄 Smart File Operations
Professional file management features:
- Intelligent file creation and editing
- Real-time linter/compiler error monitoring
- Automatic workspace checkpointing
- Visual diff comparisons and state restoration
- Change tracking and indicators
- Configurable access control via .sakadevignore

### 🌐 Browser Testing & Debugging
End-to-end web development capabilities:
- Headless browser automation
- Element interaction and navigation
- Screenshot capture and console monitoring
- Runtime debugging and issue resolution
- End-to-end testing workflows
- Local Chrome debugging support

### 🔧 Extensible Tool System
Create custom capabilities via MCP:
- On-demand tool creation and installation
- Integration with existing MCP servers
- HTTP and SSE transport support
- Fine-grained permission controls
- Rich response formatting
- Community tool marketplace

### 🔍 Context-Aware Development
Efficient project understanding:
- URL content import as markdown (@url)
- Workspace diagnostics integration (@problems)
- Direct file access and bulk import (@file, @folder)
- Plan/Act mode workflow optimization
- Smart context window management
- Intelligent task organization

## Development

### Contributing
Check our [open issues](https://github.com/rahmanazhar/SakaDev/issues) or [feature request board](https://github.com/rahmanazhar/SakaDev/discussions/categories/feature-requests?discussions_q=is%3Aopen+category%3A%22Feature+Requests%22+sort%3Atop) to get started.

### Local Setup
<details>
<summary>Local Development Instructions</summary>

1. Clone the repository _(Requires [git-lfs](https://git-lfs.com/))_:
    ```bash
    git clone https://github.com/rahmanazhar/SakaDev.git
    ```
2. Open the project in VSCode:
    ```bash
    code sakadev
    ```
3. Install the necessary dependencies for the extension and webview-gui:
    ```bash
    npm run install:all
    ```
4. Launch by pressing `F5` (or `Run`->`Start Debugging`) to open a new VSCode window with the extension loaded. (You may need to install the [esbuild problem matchers extension](https://marketplace.visualstudio.com/items?itemName=connor4312.esbuild-problem-matchers) if you run into issues building the project.)

</details>

<details>
<summary>Creating a Pull Request</summary>

1. Before creating a PR, generate a changeset entry:
    ```bash
    npm run changeset
    ```
   This will prompt you for:
   - Type of change (major, minor, patch)
     - `major` → breaking changes (1.0.0 → 2.0.0)
     - `minor` → new features (1.0.0 → 1.1.0)
     - `patch` → bug fixes (1.0.0 → 1.0.1)
   - Description of your changes

2. Commit your changes and the generated `.changeset` file

3. Push your branch and create a PR on GitHub. Our CI will:
   - Run tests and checks
   - Changesetbot will create a comment showing the version impact
   - When merged to main, changesetbot will create a Version Packages PR
   - When the Version Packages PR is merged, a new release will be published

</details>


## License
[Apache 2.0 © 2025 SakaDev by Rahman Azhar.](./LICENSE)
