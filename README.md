# LTR-on-graphs-and-experiements-with-DeIT

A weighted data graph G = (V, E, w) is given, where V = v1, ..., vn is a finite set of
vertices representing objects or data points, E ⊆ V × V is a set of edges, and
w : E → R is a weight function. Additionally, a small number of examples of
preferences or order relationships among objects in V are given. The preferences can
be represented as a weighted preference graph Γ = (V, Σ, τ ), where Σ ⊆ V × V and
τ : Σ → R indicates the penalty for mis-ordering a pair. The goal is to learn a
ranking function f : V → R that accurately ranks the remaining objects in
V in descending order of the scores f(vi), given ⟨G, Γ⟩.
