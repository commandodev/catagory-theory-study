# Phase 1: Bridging Haskell to Mathematical Categories
**Duration**: 6-8 weeks | **Text**: Riehl Ch. 1-2

## Overall Progress: ⬜⬜⬜⬜⬜⬜ (0/6 weeks)

## Week 1-2: Categories as Generalized Hask
**Status**: Not Started
**Progress**: ⬜⬜⬜⬜⬜ (0/5)

### Reading
- [ ] Riehl 1.1: Abstract and concrete categories
- [ ] Riehl 1.2: Duality

### Haskell Bridge
- [ ] Understand `Hask` as a category
  - [ ] Objects = Haskell types
  - [ ] Morphisms = Haskell functions  
  - [ ] Prove `(.)` is associative with `id` as identity

### Exercises
- [ ] Riehl 1.1.i: Verify category axioms for Set
- [ ] Riehl 1.1.ii: Show Mat_k is a category
- [ ] Implement a `Category` typeclass in Haskell

### Mathematical Skills
- [ ] Direct proof technique
- [ ] Reading commutative diagrams

### Key Insights
- [ ] _To be filled as learned_

### Notes
_Space for observations, questions, and connections_

---

## Week 3-4: Functors - Beyond `fmap`
**Status**: Not Started
**Progress**: ⬜⬜⬜⬜⬜ (0/5)

### Reading
- [ ] Riehl 1.3: Functoriality

### Haskell Bridge
- [ ] From `Functor` instances to mathematical functors
- [ ] Prove functor laws for `[]`, `Maybe`, `Either e`
- [ ] Understand contravariant functors
- [ ] Connect to Lens libraries

### Set Theory Foundation
- [ ] Functions as relations
- [ ] Injections, surjections, bijections
- [ ] Function composition properties

### Exercises
- [ ] Riehl 1.3.i: Functors preserve isomorphisms
- [ ] Riehl 1.3.iv: Free/forgetful functors
- [ ] Implement `Contravariant` in Haskell

### Mathematical Notation
- [ ] Function composition notation
- [ ] Commutative diagram notation

### Key Insights
- [ ] _To be filled as learned_

---

## Week 5-6: Natural Transformations and Parametricity  
**Status**: Not Started
**Progress**: ⬜⬜⬜⬜⬜⬜ (0/6)

### Reading
- [ ] Riehl 1.4: Naturality
- [ ] Riehl 1.5: Equivalence of categories
- [ ] Riehl 1.6: The art of the diagram chase

### Haskell Bridge
- [ ] Every polymorphic function is natural!
- [ ] Why `reverse :: [a] -> [a]` commutes with `map`
- [ ] Connect to parametricity theorem
- [ ] Natural transformations as morphisms between functors

### Diagram Chasing
- [ ] Learn to read commutative diagrams
- [ ] Practice "element chasing" proofs
- [ ] Understand diagram pasting

### Exercises
- [ ] Riehl 1.4.ii: Natural transformations between hom-functors
- [ ] Prove naturality of standard Haskell functions
- [ ] Riehl 1.5.iv: Equivalences of categories

### Key Insights
- [ ] _To be filled as learned_

---

## Phase 1 Summary

### Concepts Mastered
- [ ] Category definition and examples
- [ ] Functors and their properties
- [ ] Natural transformations
- [ ] Basic diagram chasing

### Mathematical Skills Developed
- [ ] Direct proof techniques
- [ ] Working with abstract definitions
- [ ] Reading mathematical notation
- [ ] Constructing counterexamples

### Haskell Connections Made
- [ ] Hask as a category
- [ ] Functor laws in practice
- [ ] Parametricity as naturality

### Ready for Phase 2?
- [ ] Comfortable with categorical language
- [ ] Can work with commutative diagrams
- [ ] Understand the concept of universal properties
- [ ] Ready to tackle Yoneda lemma
