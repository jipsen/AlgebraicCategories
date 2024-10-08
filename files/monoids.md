=====Monoids=====

Abbreviation: **Mon**
====Definition====
A \emph{monoid} is a structure $\mathbf{M}=\langle M,\cdot
,e\rangle $, where $\cdot $ is an infix binary operation, called the 
\emph{monoid product}, and $e$ is a constant (nullary operation), called the 
\emph{identity element} , such that


$\cdot $ is associative:  $(x\cdot y)\cdot z=x\cdot (y\cdot z)$


$e$ is an identity for $\cdot $:  $e\cdot x=x$, $x\cdot e=x$.
==Morphisms==
Let $\mathbf{M}$ and $\mathbf{N}$ be monoids. A morphism from $\mathbf{M}$
to $\mathbf{N}$ is a function $h:Marrow N$ that is a homomorphism: 

$h(x\cdot y)=h(x)\cdot h(y)$, $h(e)=e$

====Examples====
Example 1: $\langle X^{X},\circ ,id_{X}\rangle $, the collection of
functions on a sets $X$, with composition, and identity map.

Example 1: $\langle M(V)_{n},\cdot ,I_{n}\rangle $, the collection of $n\times n$ matrices over a vector space $V$, with matrix multiplication and
identity matrix.

Example 1: $\langle \Sigma ^{\ast },\cdot ,\lambda \rangle $, the collection
of strings over a set $\Sigma $, with concatenation and the empty string.
This is the free monoid generated by $\Sigma $.



====Basic results====

====Properties====
^[[Classtype]]  |Variety |
^[[Equational theory]]  |decidable in polynomial time |
^[[Quasiequational theory]]  |undecidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |no |
^[[Congruence modular]]  |no |
^[[Congruence n-permutable]]  |no |
^[[Congruence regular]]  |no |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  |no |
^[[Strong amalgamation property]]  |no |
^[[Epimorphisms are surjective]]  |no |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &2\\
f(3)= &7\\
f(4)= &35\\
f(5)= &228\\
f(6)= &2237\\
f(7)= &31559\\
\end{array}$

====Subclasses====
[[Cancellative monoids]] 

[[Commutative monoids]] 

====Superclasses====
[[Semigroups]] 

[[Partial monoids]] 


====References====

[(Ln19xx>
)]