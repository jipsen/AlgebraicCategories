# Boolean algebras

Abbreviation: **BA** 

A ***Boolean algebra*** is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,-\rangle$ of type $\langle 2,0,2,0,1\rangle$
such that

$0,1$ are identities for $\vee,\wedge$:  $x\vee 0=x$, $x\wedge 1=x$

$-$ gives a complement:  $x\wedge -x=0$, $x\vee -x=1$

$\vee,\wedge$ are associative:  $x\vee (y\vee z)=(x\vee y)\vee z$, $x\wedge (y\wedge z)=(x\wedge y)\wedge z$

$\vee,\wedge$ are commutative:  $x\vee y=y\vee x$, $x\wedge y=y\wedge x$

$\vee,\wedge$ are mutually distributive:  $x\wedge (y\vee z)=(x\wedge y)\vee (x\wedge z)$, $x\vee (y\wedge z)=(x\vee y)\wedge (x\vee z)$

## Definition
A ***Boolean algebra*** is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,-\rangle$ of type $\langle 2,0,2,0,1\rangle$
such that

$\langle A,\vee ,0,\wedge ,1\rangle$ is a 
[bounded distributive lattice](bounded_distributive_lattices.md)

$-$ gives a complement:  $x\wedge -x=0$, $x\vee -x=1$

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(-x)=-h(x)$

It follows that $h(x\wedge y)=h(x)\wedge h(y)$, $h(0)=0$, $h(1)=1$.

## Definition
A ***Boolean ring*** is a structure $\mathbf{A}=\langle A,+
,0,\cdot ,1\rangle$ of type $\langle 2,0,2,0\rangle$
such that

$\langle A,+ ,0,\cdot ,1\rangle$ is a [commutative ring with unit](commutative_ring_with_units.md)

$\cdot$ is idempotent:  $x\cdot x=x$

Remark: 
The term-equivalence with Boolean algebras is given by $x\wedge y=x\cdot y$, $-x=x+1$, $x\vee y=-(-x\wedge -y)$ and 
$x+y=(x\vee y)\wedge -(x\wedge y)$.

## Definition
A ***Boolean algebra*** is a [Heyting algebra](heyting_algebras.md) $\mathbf{A}=\langle
A,\vee ,0,\wedge ,1,\to\rangle$ such that

$\to 0$ is an involution:  $(x\to 0)\to 0=x$

## Examples
Example 1: $\langle \mathcal P(S), \cup ,\emptyset, \cap, S, -\rangle$, the
collection of subsets of a sets $S$, with union, intersection, and
setcomplementation.


## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  |decidable in NPTIME |
|[Quasiequational theory](quasiequational_theory.md)  |decidable |
|[First-order theory](first-order_theory.md)  |decidable |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |yes |
|[Equationally def. pr. cong.](equationally_def._pr._cong..md)  |yes |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |
|[Locally finite](locally_finite.md)  |yes |
|[Residual size](residual_size.md)  |2 |

## Finite members
Number of algebras $=\{ 
\begin{array}{cc}
1 & \text{if size}=2^{n} \\ 
0 & \text{otherwise}\end{array}.$


## Subclasses
[One-element algebras](one-element_algebras.md) 

[Complete Boolean algebras](complete_boolean_algebras.md) 


## Superclasses
[Bounded distributive lattices](bounded_distributive_lattices.md) 

[Generalized Boolean algebras](generalized_boolean_algebras.md) 

[Heyting algebras](heyting_algebras.md) 


## References
