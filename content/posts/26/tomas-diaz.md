+++
date = '2026-12-16T16:00:00'
draft = false
title = 'Tomás Díaz'
charlista = 'Tomás Díaz'
website = "https://pleiad.cl/people/tdiaz"
tituloCharla = ''
afiliacion = 'Universidad de Chile / Nantes Université'
next = true
link = "https://univ-nantes-fr.zoom.us/j/86280829504?pwd=TySS0e7FoDBdqlSxCl7lM0YUBc3nr3.1"
slides = ""
abstract = """
Certified programming allows developers to build software alongside machine-checked proofs of correctness. However, while software development is inherently incremental, certified programming remains mostly an all-or-nothing, post-hoc effort because proof assistants have no specific support for incrementality, and specifications and proof scripts are rarely designed to accommodate intermediate incomplete program definitions. In this talk, I will present systematic support for incremental certified programming (ICP). To this end, we first develop a formal framework for stating and proving properties of incomplete programs, implement it in the Rocq Prover, and apply it to CompCert, QuickChick, and Fiat. These experiments show that exceptions are the most lightweight way to represent missing code, but they compromise the consistency of the type theory and have no practical implementation in proof assistants. Towards making them practical, we contributed to Bounded Sort Polymorphism, an extension of Rocq’s sort polymorphism with elimination constraints, which provides native support for keeping exceptions in sorts of their own without a dedicated kernel extension. Building on it, I finally present IncRocq, a framework for ICP in Rocq with program holes confined to a dedicated sort and extends the previous framework with incremental proof scripts.
"""
+++