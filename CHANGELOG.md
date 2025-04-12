# Changelog

All notable changes to SakaDev will be documented in this file.

## [3.1.0] 🐛 Major Improvements
- Redesign checkpoint UI to declutter chat view by using a subtle indicator line that expands to a popover on hover, with a new date indicator for when it was created
- Add support for xAI's provider's Grok 3 models
- Add more robust error tracking for users opted in to telemetry (thank you for helping us make SakaDev better!)
- Add CMD+' keyboard shortcut to add selected text to SakaDev
- SakaDev now auto focuses the text field when using 'Add to SakaDev' shortcut
- Add new 'Create New Task' tool to let SakaDev start a new task autonomously!
- Fix Mermaid diagram issues
- Fix Gemini provider cost calculation to take new tiered pricing structure into account
- Add setting to let browser tool use local Chrome via remote debugging, enabling session-based browsing. Replaces sessionless Chromium, unlocking debugging and productivity workflows tied to your real browser state.
- Add new auto-approve option to approve _ALL_ commands (use at your own risk!)
- Add modal in the chat area to more easily enable or disable MCP servers
- Add drag and drop of file/folders into sakadev chat (Thanks eljapi!)
- Add prompt caching for LiteLLM + Claude (Thanks sammcj!)
- Add Improved context management
- Fix MCP auto approve toggle issues being out of sync with settings
- Add recommended models for SakaDev provider
- Add ability to detect when user edits files manually so SakaDev knows to re-read, leading to reduced diff edit errors
- Add improvements to file mention searching for faster searching
- Add scoring logic to file mentions to sort and exlcude results based on relevance
- Add Support for Bytedance Doubao (Thanks Tunixer!)
- Fix to prevent duplicate BOM (Thanks bamps53!)
- Add Gemini 2.5 Pro Preview 03-25 to Google Provider
- Add Enable extended thinking for LiteLLM provider (Thanks @jorgegarciarey!)
- Add a tab for configuring local MCP Servers
- Fix issue with DeepSeek API provider token counting + context management
- Fix issues with checkpoints hanging under certain conditions
- Add UI for adding remote servers
- Add Mentions Feature Guide and update related documentation
- Fix bug where menu would open in sidebar and open tab
- Fix issue with SakaDev accounts not showing user info in popout tabs
- Fix bug where menu buttons wouldn't open view in sidebar
- Add support for remote MCP Servers using SSE
- Add gemini-2.5-pro-exp-03-25 to Vertex AI (thanks @arri-cc!)
- Add access to history, mcp, and new task buttons in popout view
- Add task feedback telemetry (thumbs up/down on task completion)
- Add toggle disabled for remote servers
- Move the MCP Restart and Delete buttons and add an auto-approve all toggle
- Update Requestly UX for model selection (thanks @arafatkatze!)
- Add escape for html content for gemini when running commands
- Improve search and replace edit failure behaviors
- Add Sambanova Deepseek-V3-0324
- Add cost calculation support for LiteLLM provider
- Fix bug where SakaDev would use plan_mode_response bug without response parameter
- Add support for SambaNova QwQ-32B model
- Add OpenAI "dynamic" model chatgpt-4o-latest
- Add Amazon Nova models to AWS Bedrock
- Improve file handling for NextJS folder naming (fixes issues with parentheses in folder names)
- Add Gemini 2.5 Pro to Google AI Studio available models
- Handle "input too large" errors for Anthropic
- Fix "See more" not showing up for tasks after task un-fold
- Fix gpt-4.5-preview's supportsPromptCache value to true

## [3.0.10] 🐛 Bug Fixes
- Fixed Context Menu UI issues
- Fix TerminalManager error handling

## [3.0.4] 🐛 Bug Fixes
- Fixed Gemini models adding code block artifacts to text content
- Fixed context mention menu visual issues on light themes
- Fixed icon-related bugs

## [3.0.2] 🔧 Improvements
- Enhanced diff editing reliability:
  - Added block anchor matching for 3+ line blocks
  - Improved system prompt for complete line handling
  - Enhanced diff edit error handling
- Added support for new Gemini models

## [3.0.0] 🚀 Major Release
### New Features
- Implemented search & replace diff approach for large file edits
- Added comprehensive auto-approve configuration
- Introduced system notifications for approvals and task completion
- Added support for `.sakadevrules` file for project-specific instructions

## [2.2.0] 🛠️ Features
- Introduced Model Context Protocol (MCP) support:
  - Custom tools integration (web-search, GitHub, etc.)
  - MCP server management tab
  - Dynamic MCP server creation

## [2.1.x] Series
### 2.1.6
- Added LM Studio API provider support

### 2.1.5
- Added prompt caching for new Claude model IDs on OpenRouter

### 2.1.4
- Improved AWS Bedrock support:
  - Added missing regions
  - Added cross-region inference
  - Added support for older Sonnet model

### 2.1.3
- Added Claude 3.5 Haiku support (66% more cost-effective)

### 2.1.2
- Updated README with browser feature
- Fixed various bugs

### 2.1.1
- Enhanced prompt safety during browser sessions

### 2.1.0
- Implemented Anthropic's "Computer Use" feature:
  - Browser control capabilities
  - Interactive debugging
  - End-to-end testing
  - General web interaction

## [2.0.x] Series
### Features & Improvements
- Enhanced file editing and handling
- Improved model support and compatibility
- Added code omission detection
- Refined system prompts
- Enhanced cursor behavior during file edits

### Bug Fixes
- Fixed model-specific issues
- Improved request handling
- Enhanced editor integration
- Fixed streaming and UI issues

## [2.0.0] 🎉 Major Release
- Rebranded as SakaDev
- Added streaming responses with visual feedback
- Introduced Cancel button for task control
- Optimized tool calling prompt (~40% fewer requests)
- Added OpenRouter model support

## [1.9.x] Series
### Features
- Added Gemini model support
- Improved system prompt handling
- Enhanced browser integration
- Refined error handling

## [1.8.0] 📝 Context Features
- Added @ commands for context:
  - @url: URL content import
  - @problems: Workspace diagnostics
  - @file: Direct file content access
  - @folder: Bulk folder import

## [1.7.0] 🔍 Monitoring
- Added problems monitoring for proactive error fixing

## [1.6.x] Series
- Added multiple API provider support
- Improved terminal integration
- Enhanced task management
- Added fuzzy search

## [1.5.x] Series
### Features
- Added file Timeline integration
- Improved terminal emulation
- Added file editing capabilities
- Enhanced search functionality

## [1.4.0] 🔧 Improvements
- Added read-only operations setting
- Implemented sliding window context
- Added Cloud provider support
- Enhanced system prompts

## [1.3.0] - [1.0.x] Series
### Key Features
- Added task history
- Implemented prompt caching
- Added image support
- Enhanced CLI interaction
- Improved project analysis
- Added diff view support

## [0.0.6]
- Initial release

For more detailed information about each release, please visit our [GitHub releases page](https://github.com/rahmanazhar/SakaDev/releases).
