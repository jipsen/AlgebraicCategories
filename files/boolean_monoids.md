# Boolean monoids

Abbreviation: **BMon**
## Definition
A ***Boolean monoid*** is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,\cdot,e\rangle$ such that


$\langle A,\vee,0,
\wedge,1,\neg\rangle$ is a [Boolean algebra](boolean_algebras.md)


$\langle A,\cdot,e\rangle$ is a [monoids](monoids.md)


$\cdot$ is ***join-preserving*** in each argument:  
$(x\vee y)\cdot z=(x\cdot z)\vee (y\cdot z) \text{ and } x\cdot (y\vee z)=(x\cdot y)\vee (x\cdot z)$


$\cdot$ is ***normal*** in each argument:  $0\cdot x=0 \text{ and } x\cdot 0=0$


Remark: 

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean monoids. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a Boolean homomorphism and preserves $\cdot$, $e$:

$h(x\cdot y)=h(x)\cdot h(y) \text{ and } h(e)=e$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |variety |
|[Equational theory](equational_theory.md)  | |
|[Quasiequational theory](quasiequational_theory.md)  | |
|[First-order theory](first-order_theory.md)  | |
|[Locally finite](locally_finite.md)  |no |
|[Residual size](residual_size.md)  |unbounded |
|[Congruence distributive](congruence_distributive.md)  |yes |
|[Congruence modular](congruence_modular.md)  |yes |
|[Congruence n-permutable](congruence_n-permutable.md)  |yes, $n=2$ |
|[Congruence regular](congruence_regular.md)  |yes |
|[Congruence uniform](congruence_uniform.md)  |yes |
|[Congruence extension property](congruence_extension_property.md)  |yes |
|[Definable principal congruences](definable_principal_congruences.md)  |no |
|[Equationally def. pr. cong.](equationally_def._pr._cong..md)  |no |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &0\\
f(4)= &9\\
f(5)= &0\\
f(6)= &0\\
f(7)= &0\\
f(8)= &258\\
\end{array}$

## Subclasses
[Sequential algebras](sequential_algebras.md) 

## Superclasses
[Boolean algebras with operators](boolean_algebras_with_operators.md) 


## References


)]