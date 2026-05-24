+++
date = "2026-05-27T16:00:00"
draft = false
title = 'Matías Toro'
charlista = 'Matías Toro'
tituloCharla = 'Flexible and Expressive Typed Path Patterns for GQL'
afiliacion = 'Universidad de Chile'
next = true
link = "TBD"
website = "https://matiastoro.github.io/"
abstract = """
Graph databases have become an important data management technology across various domains, including biology, sociology, industry (e.g. fraud detection, supply chain management, financial services), and investigative journalism, due to their ability to efficiently store and query large-scale knowledge graphs and networks. Recently, the Graph Query Language (GQL) was introduced as a new ISO standard providing a unified framework for querying graphs. However, this initial specification lacks a formal type system for query validation. As a result, queries can fail at runtime due to type inconsistencies or produce empty results without prior warning. Solving this issue could have great benefits for users in writing correct queries, especially when handling large datasets. To address this gap, we introduce a formal type model for a core fragment of GQL extended with property-based filtering and imprecise types both in the schema and the queries. This model, named FPPC, enables static detection of semantically incorrect and stuck queries, improving user feedback. We establish key theoretical properties, including emptiness (detecting empty queries due to type mismatches) and type safety (guaranteeing that well-typed queries do not fail at runtime). Additionally, we prove a gradual guarantee, ensuring that removing type annotations either does not introduce static type errors or only increases the result set. By integrating imprecision into GQL, FPPC offers a flexible solution for handling schema evolution and incomplete type information. This work contributes to making GQL more robust, improving both its usability and its formal foundation.
"""
+++