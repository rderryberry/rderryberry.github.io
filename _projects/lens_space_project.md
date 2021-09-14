---
layout: page
title: Theory X on lens spaces
description: A class of novel 3d topological field theories
img:
importance: 4
category: work
---

<p style="color: blueviolet; font-style: italic;">This project is joint with <a href="https://www.its.caltech.edu/~monica/">Monica Kang</a>.</p>

One important source of physical dualities in recent years is the six dimensional $$\mathcal{N}=(2,0)$$ superconformal field theory affectionately known as "Theory $$\mathfrak{X}$$". Theory $$\mathfrak{X}$$ in particular provides a 6d origin for the geometric Langlands conjecture {% cite Witten09 -f research-bib %}, the AGT correspondence {% cite AGT10 -f research-bib %}, and (importantly for this project) the 3d-3d correspondence {% cite DGG13 DGG14 -f research-bib %}. Roughly, for two 3-manifolds $$M_1$$ and $$M_2$$ the 3d-3d correspondence identifies the partition function of the compactified theory $$\mathfrak{X}[M_1]$$ on $$M_2$$ with the partition function of $$\mathfrak{X}[M_2]$$ on $$M_1$$ by relating both of them to the partition function of $$\mathfrak{X}$$ on $$M_1\times M_2$$.

In this project we are investigating the situation where one of the 3-manifolds is a lens space $$L(p,q)$$. More precisely, we are interested in compactifying a 4d-topological/2d-holomorphic twist $$\mathfrak{X}^{twist}$$ of Theory $$\mathfrak{X}$$ on a lens space equipped with a transversely holomorphic foliation {% cite Closset_2014 -f research-bib %}. This structure is precisely what is needed for the compactification to "eat up" the two holomorphic directions and one of the topological directions, in principle leaving us with a three dimensional topological quantum field theory (TQFT).

Previous work in the literature has shown that for $$L(p,1)$$ type lens spaces the remaining 3d theory is a complex Chern-Simons theory with level determined by $$p$$ and the transversely holomorphic foliation on $$L(p,1)$$ {% cite CJ17 Mik18 -f research-bib %}. Compactifying on $$L(p,q)$$ with $$q\neq1$$ coprime to $$p$$ will yield a family of previously unknown 3d TQFTs - a naive but ultimately incorrect attempt at compactification suggests that these theories might be deserving of the moniker *complex Chern-Simons at fractional level* - and consequently a family of new topological invariants for 3-manifolds $$M$$ given by the resulting partition functions $$\mathfrak{X}^{twist}[L(p,q)](M)$$. Via the 3d-3d correspondence, these 3-manifold invariants can alternately be interpreted physically as the lens space partition functions of a different theory: namely the 1d-topological/2d-holomorphic theory $$\mathfrak{X}^{twist}[M]$$.

Interestingly, the compactification on general $$L(p,q)$$ turns out to be significantly harder than the $$L(p,1)$$ case already treated in the literature. The (comparative!) simplicity of the $$L(p,1)$$ case ultimately boils down to the fact that in this case the resulting theory has a weakly coupled description:
- In the approach of C&oacute;rdova and Jafferis {% cite cordova2013 -f research-bib %} the description of $$L(p,1)$$ as a circle bundle over $$S^2$$ is used to reduce the problem to 5d $$\mathcal{N}=2$$ supersymmetric Yang-Mills (SYM) in a particular supergravity background.
- Alternately, in the approach of Mikhaylov {% cite Mik18 -f research-bib %} $$L(p,1)$$ is represented as a degenerate torus fibration over a closed interval $$I$$, and so via torus reduction the problem is factored through a Janus configuration {% cite Gaiotto_2010 -f research-bib %} of 4d $$\mathcal{N}=4$$ SYM on the product manifold $$I\times M$$. It is shown that the left hand boundary condition is of type $$(\pm1,0)$$ and the right hand boundary condition is of type $$(\pm 1,\pm p)$$, which correspond to inserting terms proportional to the Chern-Simons action functional supported on the boundaries into the path integral.

Neither of these approaches generalises to the other $$L(p,q)$$ lens spaces, and we in fact expect that the 3d topological theory $$\mathfrak{X}^{twist}[L(p,q)]$$ will *not* have a weakly coupled description. This novelty makes the theory interesting, however it also makes the problem of describing it (e.g. in a functorial manner) extremely difficult. As an intermediate step, we are currently investigating the circle compactification of the this theory, i.e. the 2d TQFT $$\mathfrak{X}^{twist}[L(p,q)\times S^1]$$: as this theory factors though a twist of 5d $$\mathcal{N}=2$$ SYM it has a Lagrangian description, and we plan to study the properties of this 2d theory in order to determine potential properties and candidates for the full 3d TQFT.

---

#### References:

{% bibliography -f research-bib --cited -T bib_proj %}
