# MOKACLAW

Mokaclaw is a Git-native Agentic Prompt Operating System.

It enables deterministic software engineering workflows using LLM agents through structured prompt composition.

## Core Concept

This system does NOT implement runtime agents.

It defines a composable prompt architecture that an external orchestrator (e.g. OpenClaw) interprets and executes.

## Execution Model

User Request
→ Orchestrator
→ Workflow Selection
→ Planner
→ Coder
→ Reconciliation (policy-based)
→ Git Commit