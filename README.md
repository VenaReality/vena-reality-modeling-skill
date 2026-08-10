# Vena Reality Modeling Skill

> A lightweight AI reasoning skill based on Vena Reality Methodology, enabling reality-first analysis before modeling, decision-making, and solution generation.
Vena Reality helps reduce cognitive contamination in AI reasoning by forcing models to examine reality structures before generating solutions.

Version: 0.1.0

---

# Overview

Vena Reality Modeling Skill is a lightweight AI-oriented implementation of the Vena Reality Methodology.

It is not the complete Vena Reality framework itself.

Instead, it extracts the core reasoning protocol of Vena Reality and makes it usable as an AI Skill.

The purpose is to help AI agents start from reality itself:

- Before accepting a problem definition
- Before building a model
- Before designing a solution
- Before making strategic recommendations

The core principle:

> Before changing reality, understand the reality that creates the current situation.

---

# What Is Vena Reality Methodology?

Vena Reality Methodology is a reality-first thinking approach.

It focuses on understanding the factors that determine:

- The current state of a situation
- The direction of change
- The possible outcomes

Reality is not only facts.

A complete reality structure includes:

- Facts
- Constraints
- Variables
- Boundaries
- Relationships
- Observers
- Human Factors
- Business Essence
- Forces / Trends

The goal is not to collect more information.

The goal is to identify the structures that actually produce the observed reality.

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


This approach is valuable for organizing known information.

However, complex real-world problems often appear before complete representations exist.

They contain:

- Ambiguous problem definitions
- Hidden constraints
- Conflicting interests
- Human behaviors
- Organizational factors
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
- What factors create the current state?
- What structures influence the outcome?
- How will reality evolve?

Its core question:

> What reality produces what we observe?

Vena Reality attempts to understand the terrain that generates the map.

---

# Core Reasoning Process

Vena Reality guides AI through the following process:


Problem
↓
Problem Examination

Is this the real problem?
Who defines this problem?
What perspective shapes this definition?

↓
Reality Capture

Facts
Constraints
Variables
Relationships
Observers
Human Factors
Business Essence
Forces

↓
Reality Modeling

Build a structural understanding

↓
Decision and Action

Design solutions based on reality


---

# Reality Model

A Vena Reality Model includes:


Facts

Constraints

Variables

Boundaries

Relationships

Observers

Human Factors

Business Essence

Forces / Trends


The purpose is to identify the factors that influence:

- Current state
- Evolution direction
- Final outcome

---

# Scope of This Skill

This repository contains the core reality reasoning layer.

The examples currently included mainly demonstrate business-related reality analysis.

However, Vena Reality Methodology is not limited to business analysis.

Future extensions may include:

## Reality Product Modeling

Using reality analysis for:

- Product definition
- User needs
- Product boundaries
- Capability design
- Product evolution

## Reality Modeling

Using reality analysis for:

- Complex systems
- Enterprise architecture
- Organizational structures
- Decision models

## Reality Strategy

Using reality analysis for:

- Strategic choices
- Industry evolution
- Competitive positioning
- Long-term direction

The current Skill represents the foundation layer.

---
# Related Work

Vena Reality Methodology is also the foundation of broader enterprise decision intelligence systems.

Based on the same reality-first principles, Vena has developed:

## Vena Decision Intelligence System

Vena Decision Intelligence System applies Reality Modeling principles to enterprise decision processes.

It extends reality analysis into areas including:

- Decision evaluation
- Architecture review
- Solution optimization
- Decision governance
- Quality control mechanisms

The complete system is broader than this Skill repository and is not included here.

To make parts of the methodology more accessible, lightweight components such as architecture review gates and decision evaluation frameworks may be released independently.

The current repository focuses on the foundation layer:

Understand Reality
↓
Build Reality Model
↓
Improve Decision Quality

The purpose is to help AI systems and humans make better decisions by understanding the reality behind problems before taking action.



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
- Product analysis
- Product design
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
- Structure generation

However, many failures happen because AI reasons from an incomplete or incorrect problem definition.

Vena Reality introduces an earlier reasoning layer:

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

# Examples

The repository includes several Meta Cases from Vena Reality Methodology.

These examples are not intended as simple business case studies.

They demonstrate how reality-first reasoning identifies hidden assumptions, constraints, human factors, and structural conditions behind decisions.

Examples:

- Refrigerator Case: Understanding human demand reality beyond product functions.
- Alipay Social Case: Understanding relationship reality and user mental models.
- Fetion Case: Understanding organizational system reality and evolution capability.

---

# License

MIT License