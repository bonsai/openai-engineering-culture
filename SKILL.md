---
name: openai-engineering-culture
description: Apply OpenAI-style engineering and research culture principles. Use when advising on AI team culture, full-stack AI development, bottom-up ideation, experiment-driven workflows, reducing experiment friction, validation over debate, or cross-functional AI work. Triggers include OpenAI culture, full-stack researcher, k8s debugging by researchers, prototype first, ideas are cheap, validation data, experiment leverage, boundaryless AI teams.
---

# OpenAI Engineering Culture

## Overview

OpenAI operates with a boundaryless, bottom-up culture where researchers, infrastructure engineers, and product people move freely across concerns. Ideas are cheap; validated experiments and data are valuable. The highest-leverage organizational work is lowering the cost of running and measuring experiments.

## Core Practices

### Boundaryless ownership
- Expect and encourage people to cross traditional role boundaries.
- A researcher who understands Kubernetes, inference constraints, and deployment realities produces higher-quality research.
- An infrastructure or product person who deeply understands model behavior and training dynamics produces better systems.
- Treat "full-stack" as the default rather than the exception for impactful contributors.

### Bottom-up idea flow with high validation bar
- Anyone can propose and discuss ideas freely.
- Treat raw ideas as low-cost and abundant.
- Assign real value only to ideas that have been turned into prototypes, evaluation metrics, or measured results.
- Prefer building a small experiment or evaluation harness over prolonged debate.

### Experiment leverage as organizational priority
- Continuously ask how to make the next experiment cheaper, faster, and more informative.
- Invest in shared evaluation infrastructure, reproducible training recipes, easy ablation setups, and clear metrics.
- The organization that can run and interpret more high-quality experiments per unit time compounds its advantage.

### Reverse from user problems
- Strong contributors start from concrete user or product problems and work backward to model structure, training, and infrastructure choices.
- Avoid starting from a cool technique and searching for a problem it might solve.

## Practical Guidance

When facilitating or participating in AI technical work:
1. Surface the concrete constraint or user need first.
2. Propose the smallest prototype or evaluation that would distinguish good from bad approaches.
3. Prefer shipping a measurable experiment over perfecting the theoretical argument.
4. If someone is blocked on infrastructure or tooling, treat unblocking them as high-leverage work.
5. Celebrate cost and friction reductions in the experiment loop as first-class contributions.

## Anti-patterns
- Prolonged theoretical debate without a prototype or metric.
- Gatekeeping ideas by role or seniority.
- Treating infrastructure and evaluation tooling as secondary to "core research."
- Optimizing for the elegance of an idea rather than the quality of the evidence it can generate.
