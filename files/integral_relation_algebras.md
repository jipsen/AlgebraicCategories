=====Integral relation algebras=====

Abbreviation: **IRA** (this may also abbreviate the variety generated by all integral relation algebras)


====Definition====
An \emph{integral relation algebra} is a [[relation algebra]] $\mathbf{A}=\langle A,\vee,0,
\wedge, 1, ', \circ, ^{\smile}, e\rangle$ that is

\emph{integral}:  $x\circ y=0\Longrightarrow x=0\mbox{ or }y=0$


====Definition====
An \emph{integral relation algebra} is a [[relation algebra]] $\mathbf{A}=\langle A,\vee,0,
\wedge,1,',\circ,^{\smile},e\rangle$ in which 

\emph{the identity element $e$ is $0$ or an atom}: $e=x\vee y\Longrightarrow x=0\mbox{ or }y=0$


==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be integral relation algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x\circ y)=h(x)\circ h(y)$, $h(x\vee y)=h(x)\vee h(y)$, $h(x')=h(x)'$, $h(x^\smile)=h(x)^\smile$ and $h(e)=e$.


====Examples====
For any [[group]] $\mathbf G=\langle G,*,^{-1},e\rangle$, construct the integral relation algebra $\mathcal R(G)=\langle\mathcal P(G),\cup,\emptyset,\cap,G,',\circ,^\smile,\{e\}\rangle$, where $X\circ Y=\{x*y:x\in X,y\in Y\}$ and $X^\smile=\{x^{-1}:x\in X\}$ for $X,Y\subseteq G$.

====Basic results====
Every nontrivial integral relation algebra is simple.

Every simple [[commutative relation algebra]] is integral.

Every [[group relation algebra]] is integral.

====Properties====
^[[Classtype]]                        |universal  |
^[[Equational theory]]                |undecidable  |
^[[Quasiequational theory]]           |undecidable  |
^[[First-order theory]]               |undecidable  |
^[[Locally finite]]                   |no  |
^[[Residual size]]                    |no  |
^[[Congruence distributive]]          |yes  |
^[[Congruence modular]]               |yes  |
^[[Congruence $n$-permutable]]        |yes  |
^[[Congruence regular]]               |yes  |
^[[Congruence uniform]]               |yes  |
^[[Congruence extension property]]    |yes  |
^[[Definable principal congruences]]  |no  |
^[[Equationally def. pr. cong.]]      |no  |
^[[Amalgamation property]]            | |
^[[Strong amalgamation property]]     | |
^[[Epimorphisms are surjective]]      | |

====Finite members====
^$n$         | 1 | 2 | 4 |  8 |  16 |       32 |             64 |                     128 | 256 |
^# of algs | 1 | 1 | 2 | 10 | 102 |  4412 |  4886349 | 344809166311 |  | 

For $n\ne 2^k$, the # of algebras is 0.

See http://www1.chapman.edu/~jipsen/gap/ramaddux.html for more information.

====Subclasses====
[[Simple commutative relation algebras]]

[[Group relation algebras]]


====Superclasses====
[[Relation algebras]]


====References====

[(Ln19xx>
F. Lastname, \emph{Title}, Journal, \textbf{1}, 23--45 [[MRreview]] 
)]
