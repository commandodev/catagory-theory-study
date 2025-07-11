# Category Theory Study Journey

A structured self-study program bridging from Haskell programming expertise to rigorous mathematical category theory.

## Overview

This repository tracks my journey learning category theory, starting from my background as a professional Haskell programmer and building towards research-level mathematical understanding. The curriculum is designed to leverage programming intuitions while developing mathematical maturity.

## Background

- **Starting Point**: Professional Haskell programmer with extensive practical experience using categorical concepts (monads, functors, comonads, lenses)
- **Mathematical Background**: A-level mathematics (30 years ago), needs refreshing alongside category theory
- **Goal**: Develop world-class theoretical understanding and ability to engage with research literature

## Learning Philosophy

1. **Bridge Programming to Mathematics**: Start with familiar Haskell concepts and reveal their mathematical foundations
2. **Dual-Track Learning**: Simultaneously develop mathematical maturity and category theory expertise
3. **Progressive Rigor**: Gradually introduce proof techniques and abstract reasoning
4. **Active Learning**: Work through exercises, implement concepts, and build intuition

## Curriculum Structure

### Phase 1: Bridging Haskell to Mathematical Categories (6-8 weeks)
- Categories as generalized Hask
- Functors beyond `fmap`
- Natural transformations and parametricity
- Introduction to diagram chasing

### Phase 2: Universal Properties and Limits (6-8 weeks)
- The Yoneda Lemma
- Limits and colimits
- Universal properties as specifications

### Phase 3: Adjunctions - The Key Concept (4-5 weeks)
- Adjoint functors
- Free/forgetful adjunctions
- The centrality of adjunctions

### Phase 4: Monads as Mathematical Objects (4-5 weeks)
- Monads from adjunctions
- Algebras for monads
- The Eilenberg-Moore category

### Phase 5: Advanced Topics (6-8 weeks)
- Kan extensions
- Choice of: Topos theory, Higher categories, or Categorical logic

## Repository Structure

```
.
├── README.md                  # This file
├── system.md                  # System prompt for AI assistance
├── curriculum/               
│   ├── overview.md           # Detailed curriculum with weekly breakdowns
│   └── phase-*.md            # Individual phase descriptions
├── progress/
│   ├── current.md            # Current status (paste at session start)
│   └── phase-*.md            # Progress tracking for each phase
├── exercises/
│   ├── completed/            # Completed exercise solutions
│   └── in-progress/          # Current work
├── notes/                    # Mathematical notes, proofs, insights
└── resources/                # Links, references, key theorems
```

## How to Use This Repository

1. **Starting a Study Session**: Open `progress/current.md` and paste it into Claude
2. **During Study**: Work through exercises, take notes, update progress
3. **Ending a Session**: Update progress files and commit changes
4. **Building Knowledge**: Add key insights to notes, collect proved theorems

## Primary Resource

- **Main Text**: "Category Theory in Context" by Emily Riehl
- **Supplementary**: Various papers and online resources as needed

## Progress Tracking

Progress is tracked using markdown checkboxes in phase files. Each phase has:
- Reading assignments
- Exercises from Riehl
- Implementation projects
- Key proofs to complete
- Conceptual milestones

## Mathematical Development

Alongside category theory, developing:
- Set theory foundations
- Proof techniques (direct, contradiction, induction)
- Abstract algebra connections
- Mathematical writing skills

---

*"The aim of theory really is, to a great extent, that of systematically organizing past experience in such a way that the next generation, our students and their students and so on, will be able to absorb the essential aspects in as painless a way as possible..."* - M.F. Atiyah
