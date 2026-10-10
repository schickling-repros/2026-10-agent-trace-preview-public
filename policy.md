# Targeted convergence policy

Converge only hosts whose declared policy changed. Require an explicit host scope before activation; preserve unrelated host generations.

For a dev3-only policy change, compare the proposed dev3 generation and retain the current dev5 generation. Abort before activation if the declared scope expands. Record both revision identifiers in the review.
