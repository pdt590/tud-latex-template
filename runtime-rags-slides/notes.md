# runtime-rag-poster

## part 1.1

- problem statement
	- efficient continuous model validation (or actually general computation), but rags lack support for bidirectional references
	- trainbenchmark setting (ecore, instance model)
- initial solution
	- grammar as ebnf with namelookup
	- pattern of one query, attribute to compute this query

## part 1.2

- show our way to the solution described in the paper, and their advantages and disadvantages
- name lookup: problem with computation of inverse relation-parts
- optimized: use intrinsic relations, but still compute inverse relations
- specialized: use intrinsic relations to store both directions of relations, use preprocessor to generate grammar and boilerplate code (consistently)

## part 2

- eval
	- left: LOC, diff of transformation, statement for consistency (?)
	- right: 2-3 diagrams showing our measurements
