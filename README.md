# OOP Dojo 🥋 
**Object-Oriented Programming — principles, patterns, and production-grade design**

---

## Overview

This repository is a **deliberate, design-first exploration of Object-Oriented Programming (OOP)**.

Rather than focusing on syntax or isolated examples, it treats OOP as what it truly is in professional environments:  
a **tool for managing complexity, enforcing boundaries, and building systems that scale in people and code**.

The structure, examples, and explanations here reflect how OOP is applied in **real-world, long-lived software systems**.

---

## Intent (Without the Buzzwords)

This repository is built to:

- Demonstrate **clear reasoning about software design**
- Show **intentional use of OOP**, not accidental usage
- Make architectural decisions **visible and explainable**
- Bridge the gap between *knowing OOP* and *using OOP well*

You won’t find random snippets.  
You’ll find **choices**, and the reasoning behind them.

---

## What This Repository Emphasizes

### 1. Fundamentals With Consequences
Core OOP concepts are explored with an emphasis on:
- Responsibility
- Encapsulation boundaries
- Object collaboration

Each concept includes:
- Poor implementations (and why they fail)
- Improved designs (and what they fix)

---

### 2. Principles Over Patterns
SOLID and related principles are treated as **constraints that guide design**, not checkboxes.

Patterns are introduced only when:
- A real problem exists
- The trade-off is justified
- The alternative designs are understood

---

### 3. Realistic System Design
Examples model **actual application structure**, including:
- Domain models
- Services
- Abstractions and interfaces
- Separation of concerns

The goal is not to impress with complexity, but to show **control over it**.

---

### 4. Anti-Patterns as First-Class Citizens
Understanding what *breaks* systems is as important as knowing what builds them.

This repository includes explicit examples of:
- Over-centralized logic
- Tight coupling
- Misused inheritance
- Abstractions that hurt more than they help

Each is paired with a refactored alternative.

---

### 5. Progressive Challenges
Exercises are designed to test:
- Design judgment
- Trade-off awareness
- Ability to evolve a system without breaking it

Difficulty increases by **design complexity**, not by syntax tricks.

---

## Language Choice

The primary implementation uses **Java**.

This choice is intentional:
- Strong typing exposes design flaws early
- Interfaces and contracts are explicit
- The language encourages disciplined structure

The repository layout is language-agnostic and can be extended to other OOP languages without changing the underlying ideas.

---

## How to Read This Repository

There is no single “correct” path, but a recommended flow is:

1. Fundamentals → understand object responsibilities  
2. Principles → understand design constraints  
3. Patterns → understand reusable solutions  
4. Real-world examples → understand system composition  
5. Anti-patterns → understand failure modes  

Each section is independent but intentionally connected.

---

## Design Philosophy

> **Good OOP reduces the cost of change.**

Every class, interface, and boundary exists to answer one question:
> *“What happens when this system needs to change?”*

If a design makes change harder, it’s reconsidered — even if it looks elegant.

---

## Contributions

Contributions are welcome if they:
- Improve clarity
- Strengthen design correctness
- Expose better trade-offs
- Teach something non-obvious

Preference is given to:
- Readable designs over clever ones
- Explicit intent over implicit behavior
- Fewer responsibilities per class

See `CONTRIBUTING.md` for details.

---

## Closing Note

This repository reflects how I approach software problems:
- Think in systems
- Design before coding
- Optimize for maintainability, not novelty

If you’re reviewing this as a developer, treat it as a **design reference**.  
If you’re reviewing it professionally, it represents how I reason about **scalable, real-world software**.

---

⭐ If this repository helped sharpen your understanding of OOP, a star is appreciated.