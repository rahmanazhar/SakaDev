# Memory Bank System Guide

This document outlines the Memory Bank system, a critical component for maintaining perfect documentation and context across development sessions.

## Overview

The Memory Bank system is designed around a core constraint: periodic complete memory resets. This feature ensures comprehensive documentation by requiring all context and progress to be properly documented for future reference.

## Required Directory Structure

```
sakadev_docs/
├── productContext.md
├── activeContext.md
├── systemPatterns.md
├── techContext.md
└── progress.md
```

## Memory Bank Files

### productContext.md
Documents the fundamental project information:
- Project purpose and objectives
- Problems being solved
- Expected functionality and behavior

### activeContext.md
Tracks current development status:
- Current work in progress
- Recent system changes
- Planned next steps
(Serves as the primary source of truth)

### systemPatterns.md
Documents technical architecture:
- System construction methodology
- Key architectural decisions
- Established patterns and practices

### techContext.md
Captures technical requirements:
- Technology stack details
- Development environment setup
- Technical limitations and constraints

### progress.md
Maintains development progress:
- Completed functionality
- Remaining development tasks
- Current progress status

## Core Workflows

### 1. Task Initialization
Before starting any task:
1. Verify existence of Memory Bank files
2. Create any missing files immediately
3. Read all documentation thoroughly
4. Confirm complete context understanding

### 2. Development Process

#### Standard Development
- Follow established patterns from Memory Bank
- Update documentation after significant changes

#### Error Resolution
Implement [CONFIDENCE CHECK]:
1. Rate confidence level (0-10)
2. If confidence < 9:
   - Document known information
   - List uncertainties
   - Identify investigation needs
3. Only proceed when confidence ≥ 9
4. Document findings for future reference

### 3. Memory Bank Updates
When triggered by "update memory bank":
1. Recognize impending memory reset
2. Document current state comprehensively
3. Clearly outline next steps
4. Complete current task

### 4. Lost Context Recovery
If context becomes unclear:
1. Halt all operations immediately
2. Review activeContext.md
3. Obtain user verification of understanding
4. Begin with minimal, safe modifications

## Critical Rules

1. Never proceed without complete Memory Bank files
2. Always verify information before documentation
3. Update documentation after significant changes
4. Treat Memory Bank as the sole source of truth
5. Maintain documentation as if functionality depends on it

## Implementation Notes

- Memory Bank files must be created immediately if missing
- All documentation must be verified before use
- Documentation updates should be atomic and consistent
- Context verification is required before major changes
- Lost context requires immediate resolution

