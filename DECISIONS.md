# Project Decisions Log

This document stores important technical and product decisions made during the development of Business Insight Dashboard.

---

# Decision 1: Product First, AI Later

## Decision

The project will not start with AI development.

The first priority is building a strong product foundation and collecting structured business data.

## Reason

AI systems need reliable data.

Without business data, AI cannot provide meaningful insights.

The development order is:

Product
↓
Data Collection
↓
Data Analysis
↓
AI Intelligence

---

# Decision 2: Technology Direction

## Decision

The main technology direction:

Frontend:
Next.js + TypeScript

Backend:
Node.js + NestJS

Database:
PostgreSQL

AI Layer:
Python Services

## Reason

This architecture allows:

- Fast product development
- Scalability
- Clear separation between application logic and AI services
- Easier future team development

---

# Decision 3: Why Node.js Instead of Django

## Decision

The primary backend direction is Node.js.

## Reason

The product requires:

- Modern web application architecture
- Real-time features in future
- Strong connection with frontend technologies
- Easier full-stack development for a small team

Python will still be used later for AI and data analysis.

---

# Decision 4: Start as a Solo Founder Project

## Decision

The first version should be buildable by one person.

## Reason

Early stages require:

- Fast iteration
- Low development cost
- Understanding the complete system

Team expansion can happen after product validation.

---

# Decision 5: GitHub Documentation

## Decision

All important changes and decisions must be documented.

## Reason

The project should remain understandable even when:

- A new developer joins
- The project moves to another environment
- Development continues with another AI assistant

---

# Decision 6: Target Product Direction

## Decision

The final product direction is:

A Business Intelligence and Decision Support Platform.

Not only:

- Sales tracking
- Expense management

But eventually:

- Performance analysis
- Problem detection
- Business recommendations
- Predictive insights
