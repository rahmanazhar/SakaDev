# Changelog

All notable changes to SakaDev will be documented in this file.

## [3.0.9] 🐛 Bug Fixes
- Fixed Context Menu UI issues

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
