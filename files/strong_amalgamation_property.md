# Strong Amalgamation Property

An ***amalgam*** is a tuple 
$\langle \mathbf{A},f,\mathbf{B},g,\mathbf{C}\rangle$ such that 
$\mathbf{A},\mathbf{B},\mathbf{C}$ are structures of the same 
signature, and $f:\mathbf{A}\to\mathbf{B}$, $g:\mathbf{A}\to\mathbf{C}$
are embeddings (injective morphisms).

A class $\mathcal{K}$ of structures is said to have the
***strong amalgamation property***, or SAP for short, if for every amalgam $\langle \mathbf{A},f,\mathbf{B},g,\mathbf{C}\rangle$ with 
$\mathbf{A},\mathbf{B},\mathbf{C}\in\mathcal{K}$ and $A\ne\emptyset$
there exists a structure $\mathbf{D}\in\mathcal{K}$ and embeddings 
$f':\mathbf{B}\to\mathbf{D}$, $g':\mathbf{C}\to\mathbf{D}$ such that
$f'\circ f=g'\circ g$ and $	ext{Im}(f ')\cap 	ext{Im}(g')=	ext{Im}(f'\circ f)$,
where $	ext{Im}(f ')=\{f '(x) | x\in B\}$.

### = Properties that imply the SAP =
[Amalgamation property](amalgamation_propertys.md) and [Epimorphisms are surjective](epimorphisms_are_surjectives.md)

[Superamalgamation property](superamalgamation_propertys.md)

### = Properties implied by the SAP =
[Amalgamation property](amalgamation_propertys.md)

