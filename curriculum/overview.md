# Category Theory Curriculum - Detailed Overview

## Phase 1: Bridging Haskell to Mathematical Categories
**Duration: 6-8 weeks | Text: Riehl Ch. 1-2**

### Week 1-2: Categories as Generalized Hask
- [ ] Read Riehl 1.1: Abstract and concrete categories
- [ ] Read Riehl 1.2: Duality
- [ ] **Haskell Bridge**: Understand `Hask` as a category
  - [ ] Objects = Haskell types
  - [ ] Morphisms = Haskell functions
  - [ ] Prove `(.)` is associative with `id` as identity
- [ ] **Exercises**: 
  - [ ] Riehl 1.1.i: Verify category axioms for Set
  - [ ] Riehl 1.1.ii: Show Mat_k is a category
  - [ ] Implement a `Category` typeclass in Haskell
- [ ] **Proof Practice**: Direct proof of associativity
- [ ] **Key Insight**: Type-safe programming = rigorous mathematics

### Week 3-4: Functors - Beyond `fmap`
- [ ] Read Riehl 1.3: Functoriality
- [ ] **Haskell Bridge**: From `Functor` instances to mathematical functors
  - [ ] Prove functor laws for `[]`, `Maybe`, `Either e`
  - [ ] Understand contravariant functors (connect to Lens libraries)
  - [ ] Covariant hom-functors
- [ ] **Set Theory**: Functions as relations, injections, surjections, bijections
- [ ] **Exercises**:
  - [ ] Riehl 1.3.i: Functors preserve isomorphisms
  - [ ] Riehl 1.3.iv: Free/forgetful functors
  - [ ] Implement `Contravariant` in Haskell
- [ ] **Mathematical Notation**: Function composition, commutative diagrams

### Week 5-6: Natural Transformations and Parametricity
- [ ] Read Riehl 1.4: Naturality
- [ ] Read Riehl 1.5: Equivalence of categories
- [ ] **Haskell Bridge**: Every polymorphic function is natural!
  - [ ] Why `reverse :: [a] -> [a]` commutes with `map`
  - [ ] Connect to parametricity theorem
  - [ ] Natural transformations as morphisms between functors
- [ ] **Diagram Chasing**: Riehl 1.6
  - [ ] Learn to read and construct commutative diagrams
  - [ ] Practice "element chasing" proofs
- [ ] **Exercises**:
  - [ ] Riehl 1.4.ii: Natural transformations between hom-functors
  - [ ] Prove naturality of standard Haskell functions
  - [ ] Riehl 1.5.iv: Equivalences of categories

## Phase 2: Universal Properties and Limits
**Duration: 6-8 weeks | Text: Riehl Ch. 2-3**

### Week 7-8: The Yoneda Lemma - The Heart of Category Theory
- [ ] Read Riehl 2.1: Representable functors
- [ ] Read Riehl 2.2: The Yoneda lemma
- [ ] **Haskell Bridge**: 
  - [ ] "Tell me how to consume it, I'll tell you what it is"
  - [ ] Church encoding as Yoneda
  - [ ] `forall b. (a -> b) -> F b ≅ F a`
- [ ] **Proof Technique**: Universal property arguments
- [ ] **Exercises**:
  - [ ] Riehl 2.2.iii: Yoneda embedding is fully faithful
  - [ ] Riehl 2.2.viii: Cayley's theorem via Yoneda
  - [ ] Implement Yoneda/CoYoneda in Haskell

### Week 9-10: Universal Properties and Universal Elements
- [ ] Read Riehl 2.3: Universal properties and universal elements
- [ ] Read Riehl 2.4: The category of elements
- [ ] **Haskell Bridge**: 
  - [ ] Free constructions you use
  - [ ] Initial and terminal objects
  - [ ] Why universal properties matter for API design
- [ ] **Mathematical Maturity**: Abstract thinking with universal properties
- [ ] **Exercises**:
  - [ ] Riehl 2.3.i: Universal properties are unique up to unique isomorphism
  - [ ] Find universal properties in Haskell standard library

### Week 11-13: Limits and Colimits
- [ ] Read Riehl 3.1: Limits and colimits as universal cones
- [ ] Read Riehl 3.2: Limits in the category of sets
- [ ] Read Riehl 3.3-3.4: Preservation and representability
- [ ] **Haskell Bridge**:
  - [ ] Products = tuples `(,)`
  - [ ] Coproducts = `Either`
  - [ ] Equalizers and why Haskell lacks them
  - [ ] Pullbacks and their applications
- [ ] **Set Theory Deep Dive**: Limits in Set to build intuition
- [ ] **Exercises**:
  - [ ] Riehl 3.1.i: Limits as terminal objects
  - [ ] Riehl 3.2.i: Compute specific limits in Set
  - [ ] Design a library using universal properties

### Week 14: Complete and Cocomplete Categories
- [ ] Read Riehl 3.5: Complete and cocomplete categories
- [ ] Read Riehl 3.6: Functoriality of limits and colimits
- [ ] Read Riehl 3.8: Interactions between limits and colimits
- [ ] **Mathematical Maturity**: Size issues (3.7)
- [ ] **Exercises**: 
  - [ ] Riehl 3.5.i: Finite limits from pullbacks and terminal
  - [ ] Riehl 3.8.v: Limits commute with limits

## Phase 3: Adjunctions - The Key Concept
**Duration: 4-5 weeks | Text: Riehl Ch. 4**

### Week 15-16: Discovering Adjunctions
- [ ] Read Riehl 4.1: Adjoint functors
- [ ] Read Riehl 4.2: The unit and counit
- [ ] **Haskell Bridge**:
  - [ ] `curry`/`uncurry` as an adjunction
  - [ ] Free/forgetful patterns in your code
  - [ ] State monad via adjunctions
- [ ] **Proof Practice**: Establishing adjunctions
- [ ] **Exercises**:
  - [ ] Riehl 4.1.i: Adjunctions via hom-set isomorphism
  - [ ] Riehl 4.1.iii: Uniqueness of adjoints
  - [ ] Find 5 adjunctions in Haskell ecosystem

### Week 17-18: The Calculus of Adjunctions
- [ ] Read Riehl 4.3: Contravariant and multivariable adjunctions
- [ ] Read Riehl 4.4: The calculus of adjunctions
- [ ] Read Riehl 4.5: Adjunctions, limits, and colimits
- [ ] **Key Theorem**: Right adjoints preserve limits (RAPL)
- [ ] **Exercises**:
  - [ ] Riehl 4.5.ii: Left adjoints preserve colimits
  - [ ] Riehl 4.5.iv: Creating limits via adjunctions

### Week 19: Existence of Adjoints
- [ ] Read Riehl 4.6: Existence of adjoint functors
- [ ] **The Adjoint Functor Theorem**
- [ ] **Mathematical Maturity**: Solution set conditions
- [ ] Connect to Haskell design patterns

## Phase 4: Monads as Mathematical Objects
**Duration: 4-5 weeks | Text: Riehl Ch. 5**

### Week 20-21: Monads from Adjunctions
- [ ] Read Riehl 5.1: Monads from adjunctions
- [ ] Read Riehl 5.2: Adjunctions from monads
- [ ] **Haskell Bridge**:
  - [ ] Your `Monad` instances are shadows of adjunctions
  - [ ] Kleisli and Eilenberg-Moore constructions
  - [ ] Why "a monad is a monoid in the category of endofunctors"
- [ ] **Exercises**:
  - [ ] Riehl 5.1.iii: Every monad comes from an adjunction
  - [ ] Identify adjunctions for common Haskell monads

### Week 22-23: Monadic Functors and Algebras
- [ ] Read Riehl 5.3: Monadic functors
- [ ] Read Riehl 5.4: Canonical presentations via free algebras
- [ ] Read Riehl 5.5: Recognizing categories of algebras
- [ ] **New Perspective**: Monads encode algebraic theories
- [ ] **The Monadicity Theorem**
- [ ] **Exercises**:
  - [ ] Riehl 5.4.i: Free algebra constructions
  - [ ] Riehl 5.5.i: Beck's monadicity theorem

### Week 24: Limits and Colimits in Categories of Algebras
- [ ] Read Riehl 5.6: Limits and colimits in categories of algebras
- [ ] **Why fields are difficult**: They're not monadic over Set
- [ ] Creating and preserving algebraic structure
- [ ] **Final Project**: Design a monadic programming abstraction

## Phase 5: Advanced Topics
**Duration: 6-8 weeks | Text: Riehl Ch. 6 & Selected Topics**

### Week 25-27: Kan Extensions
- [ ] Read Riehl 6.1: Kan extensions
- [ ] Read Riehl 6.2: A formula for Kan extensions
- [ ] Read Riehl 6.3: Pointwise Kan extensions
- [ ] **The Slogan**: "All concepts are Kan extensions"
- [ ] **Haskell Applications**: Generalizing operations
- [ ] **Exercises**:
  - [ ] Riehl 6.1.i: Kan extensions as universal arrows
  - [ ] Riehl 6.2.v: Computing specific Kan extensions

### Week 28-29: Derived Functors and Applications
- [ ] Read Riehl 6.4: Derived functors as Kan extensions
- [ ] Read Riehl 6.5: All concepts
- [ ] **Applications**: Homological algebra, algebraic topology
- [ ] **Modern Developments**: ∞-categorical derived functors

### Week 30+: Choose Your Specialization

#### Track A: Topos Theory
- [ ] Toposes as generalized universes
- [ ] Sheaves and geometric morphisms
- [ ] Internal logic of a topos
- [ ] Applications to logic and geometry

#### Track B: Higher Category Theory
- [ ] 2-categories and bicategories
- [ ] Coherence problems
- [ ] ∞-categories and homotopy theory
- [ ] Applications to topology and physics

#### Track C: Categorical Logic
- [ ] Categories with structure
- [ ] Type theory and categories
- [ ] Categorical semantics
- [ ] Applications to programming language theory

## Ongoing Mathematical Development

### Set Theory Foundations (throughout)
- [ ] Week 1-3: Functions, relations, basic constructions
- [ ] Week 4-6: Cardinality, choice axiom, well-ordering
- [ ] Week 7-9: Ordinals, cardinals, transfinite recursion
- [ ] Week 10+: Category-theoretic foundations

### Proof Techniques (progressive)
- [ ] Phase 1: Direct proof, counterexamples
- [ ] Phase 2: Contradiction, contrapositive
- [ ] Phase 3: Diagram chasing, universal arguments
- [ ] Phase 4: Induction, transfinite methods
- [ ] Phase 5: Categorical arguments

### Abstract Algebra Connections
- [ ] Groups as one-object categories
- [ ] Rings and modules categorically
- [ ] Galois theory via categories
- [ ] Homological algebra

## Success Milestones

### Month 1-2
- [ ] Comfortable with categorical language
- [ ] Can read basic categorical definitions
- [ ] Connect Haskell experience to mathematics

### Month 3-4
- [ ] Construct basic categorical proofs
- [ ] Recognize universal properties
- [ ] Work with limits and colimits

### Month 5-6
- [ ] Understand adjunctions deeply
- [ ] See monads mathematically
- [ ] Ready for research literature

### Month 6+
- [ ] Engage with current research
- [ ] Develop own insights
- [ ] Contribute to the field
