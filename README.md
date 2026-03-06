# Jump24 AI Development Toolkit

This repository contains **Claude skills, agent workflows, and AI-assisted development tooling** used by **Jump24** to support and accelerate development across our Laravel projects.

As **Laravel Partners**, we focus on delivering high-quality, scalable Laravel applications. This repository helps standardise how we use AI-assisted development across our engineering teams by providing reusable tools, prompts, and workflows designed specifically for our stack.

## Purpose

The goal of this repository is to:

- Provide **Claude skills tailored to Laravel development**
- Enable **agentic coding workflows** to assist with implementation, refactoring, and debugging
- Share **reusable AI development utilities** across projects
- Standardise **AI-assisted engineering practices** at Jump24

## What You'll Find Here

### Skills

| Skill | Description |
|---|---|
| [laravel-releases](skills/laravel-releases) | Audit recent Laravel framework releases against your codebase — surfaces new features, deprecations, and breaking changes worth adopting. |

### Agent Workflows
AI-driven development flows for tasks such as feature scaffolding, refactoring, testing, and code review.

### Prompt Templates
Reusable prompts optimised for our development practices.

### Development Utilities
Tools and examples for integrating AI assistance into project workflows.

## Installing Skills

Install all skills:

```bash
npx skills add JumpTwentyFour/ai-toolkit --all
```

Install a specific skill:

```bash
npx skills add JumpTwentyFour/ai-toolkit --skill laravel-releases
```

## About Jump24

Jump24 is a **Laravel Partner agency** specialising in building robust, scalable Laravel applications and supporting engineering teams through consultancy, architecture, and delivery.

Learn more: https://jump24.co.uk
