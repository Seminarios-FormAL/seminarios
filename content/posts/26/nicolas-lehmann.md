+++
date = "2026-08-26T16:00:00"
draft = false
title = 'Nicolás Lehmann'
charlista = 'Nicolás Lehmann'
website = "https://nilehmann.github.io/"
tituloCharla = 'Foundational Constraint Solving for Expressive Refinement Typing'
afiliacion = 'Universidad de Chile'
next = true
link = "https://univ-nantes-fr.zoom.us/my/seminariosformal"
slides = "https://nilehmann.github.io/flex-talk/"
abstract = """
SMT-based program verifiers face two fundamental limits: expressiveness, because specifications must stay within the boundaries of SMT decidability, and trust, because the solver is a large, unverified artifact whose soundness bugs silently compromise every tool built on it. We address both with Flex, a foundational Constrained Horn Clause (CHC) solver built in Lean that reduces the trusted base to the kernel alone. Flex targets the CHCs that arise from refinement typing, a typing discipline that extends types with logical predicates to specify and verify correctness properties.

First, I will introduce refinement types, using Flux — a refinement type checker for Rust — to show how refinement typing reduces the problem of verification to CHC solving. Then I will show how Flex encodes CHCs as Lean propositions with existentially bound predicates and implements CHC solvers as tactics (meta-programs) that compute kernel-checkable proofs. Finally, I will demonstrate how targeting Flex as a backend for Flux lets us prove functional-correctness properties of low-level Rust libraries that lie beyond SMT's reach.
"""
+++