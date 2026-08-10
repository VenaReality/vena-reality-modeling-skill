# Vena Reality Modeling Skill

> A lightweight AI reasoning skill based on Vena Reality Methodology, enabling reality-first problem analysis before modeling and solution generation.

## Overview

Vena Reality Modeling Skill is a simplified AI-oriented implementation of the Vena Reality Methodology.

It helps AI agents analyze complex problems by starting from reality itself instead of immediately accepting existing problem definitions, data structures, or conceptual models.

The core idea:

> Before changing reality, understand the reality that creates the current situation.

---

# Why Reality-First?

Many AI systems and knowledge systems start from existing representations:


Data
↓
Concepts
↓
Relationships
↓
Representation of Reality


This approach is useful for organizing known information.

However, complex real-world problems often appear before complete information structures exist.

They contain:

- Ambiguous problem definitions
- Hidden constraints
- Conflicting interests
- Human behaviors
- Changing environments
- Unknown causal relationships

Vena Reality uses a different entry point:


Reality Situation
↓
Reality Capture
↓
Reality Structure
↓
Model Construction
↓
Decision and Action


The starting point is not existing knowledge.

The starting point is the real situation that produces the knowledge.

---

# Reality-First vs Ontology-First

## Ontology-First

Ontology focuses on:

- Entities
- Concepts
- Relationships
- Semantic representation
- Knowledge organization

Its core question:

> How do we represent what we know about reality?

Ontology builds a structured map of reality.

---

## Vena Reality

Vena Reality focuses on:

- What is actually happening?
- What factors determine the outcome?
- Why does this structure exist?
- How will it evolve?

Its core question:

> What reality produces what we observe?

Vena Reality attempts to understand the terrain that generates the map.

---

# Reality Model

A Vena Reality Model includes:


Facts
+
Constraints
+
Variables
+
Boundaries
+
Relationships
+
Observers
+
Human Factors
+
Business Essence
+
Forces / Trends


The purpose is not to collect all information.

The purpose is to identify the factors that actually influence:

- Current state
- Evolution direction
- Final outcome

---

# Example

## Question

"Our customer service efficiency is low. How should we improve it?"

## Typical AI Approach


Customer service slow
↓
Add automation
↓
Optimize workflow
↓
Improve training


## Vena Reality Approach


Customer service problem
↓
Is this the real problem?
↓
Why are service requests increasing?
↓
Analyze facts
↓
Identify constraints
↓
Understand stakeholders
↓
Find causal structure
↓
Model reality
↓
Design intervention


The goal is not to generate more suggestions.

The goal is to avoid solving the wrong problem.

---

# Use Cases

Suitable for:

- Business strategy
- Product decisions
- Enterprise architecture
- Organizational design
- Process redesign
- Governance problems
- Complex decision-making
- AI agent reasoning

Not intended for:

- Simple factual questions
- Basic translations
- Straightforward execution tasks

---

# Installation

Copy `SKILL.md` into the skill/rules directory supported by your AI agent.

Example:


skills/
└── vena-reality-modeling/
└── SKILL.md


Then reload your AI agent.

---

# Usage

After installation, ask your AI agent normally.

Example:


Analyze why our refund rate increased.
Use Vena Reality Modeling.


The agent should first analyze the reality behind the problem before generating solutions.

---

# Philosophy

AI systems are increasingly capable of:

- Information processing
- Pattern recognition
- Knowledge synthesis
- Reasoning

However, many failures happen because the AI reasons from an incomplete problem definition.

Vena Reality Modeling introduces an earlier layer:

Understanding the reality that creates the problem.

---

# Core Idea

Most systems ask:

> What should we do?

Vena Reality asks first:

> What is actually happening?

Then:


Is this the real problem?
↓
What reality creates it?
↓
What structure explains it?
↓
What should change?
↓
How can change become capability?


---

# License

MIT License