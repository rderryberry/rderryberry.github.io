---
layout: page
title: Generalised geometric Langlands
description: Generalisations of geometric Langlands from twisted S-duality
img: /assets/img/closed-string-S-duality.png
importance: 3
category: work
---

<p style="color: blueviolet; font-style: italic;">This project is joint with <a href="https://sraghavendran.github.io">Surya Raghavendran</a>.</p>

The geometric Langlands conjecture, originally formulated by Laumon, Beilinson and Drinfeld {% cite Drin83 Lau87 BD93 BD-GL -f research-bib %} and sharpened by Arinkin and Gaitsgory {% cite AG15 -f research-bib %}, is roughly the statement that the category of $$\mathcal{O}$$-modules on the moduli space of $$^LG$$ local systems on a curve $$C$$ is equivalent to the category of $$\mathcal{D}$$-modules on the moduli space of $$G$$-bundles on $$C$$. Here, $$\mathcal{O}$$ is the sheaf of functions, $$\mathcal{D}$$ is the sheaf of differential operators, and $$G$$ and $$^LG$$ are Langlands dual groups {% cite Spr98 -f research-bib %}.

In their famous paper {% cite KapWit07 -f research-bib %}, Kapustin and Witten realised that this conjectural mathematical equivalence, together with the closely related geometric Satake theorem {% cite MV07 -f research-bib %}, could be explained physically in terms of "S-duality" of $$\mathcal{N}=4$$ 4d supersymmetric Yang-Mills theory (SYM), a non-perturbative duality relating a $$G$$-gauge theory at strong coupling to an $$^LG$$-gauge theory at weak coupling.

$$S$$-duality arises from a symmetry of type IIB string theory. In {% cite RY19 -f research-bib %}, $$S$$-duality was written explicitly in a supersymmetric sector of type IIB string theory, which can be described as a topological string. In particular, the authors described a "twisted S-duality" map on the closed topological string fields which can couple to a stack of D3 branes. Applying this twisted S-duality map to a particular closed string field yields the usual geometric Langlands conjecture. However there are many other closed string fields to couple to, leading to many variations of the geometric Langlands duality to explore.

This project contains within it a number of individually interesting sub-projects:

### Hamiltonian deformations of the stack of Higgs bundles

The closed-string fields we study induce novel *deformations* of the category of sheaves on the moduli of Higgs vector bundles $$\mathcal{H}\mspace{-1 mu}\mathit{iggs}$$.  These deformations are expected to be exchanged by the duality. The first step for us in understanding and computing these deformations comes from recognizing that they arise from a Hamiltonian deformation of the shifted cotangent bundle to the moduli of Higgs bundles. In particular, there is a map from closed topological string fields on spacetime (i.e. cyclic cohomology) to functions on the shifted cotangent bundle to $$\mathcal{H}\mspace{-1 mu}\mathit{iggs}$$ (i.e. polyvector fields on $$\mathcal{H}\mspace{-1 mu}\mathit{iggs}$$).

We are currently working on computing this map explicitly, in terms of an integral transform whose integral kernel is the Chern character of a certain universal bundle.


### Compatibility between S-duality and T-duality

One consequence of S-duality, the *Dolbeault geometric Langlands conjecture*, states that after compactifying 4d $$\mathcal{N}=4$$ Yang-Mills on a Riemann surface $$C$$, the S-duality transformation in 4d becomes T-duality relating the moduli spaces of $$G$$ and $$^LG$$ Higgs bundles {% cite BJSV95 HMS95 KapWit07 -f research-bib %}. Mathematically, this is the prediction that

$$ \text{QCoh}(\mathcal{H}\mspace{-1 mu}\mathit{iggs}_G(C))\simeq\text{QCoh}(\mathcal{H}\mspace{-1 mu}\mathit{iggs}_{^LG}(C)), $$

which has been borne out in various levels of generality for dense open subsets of each side, but most prominently by Hausel and Thaddeus in type A and Donagi and Pantev for arbitrary reductive groups {% cite HauTha03 DonPan12 A13 AF16 Der20 -f research-bib %}.

In all cases, this equivalence is implemented by a Fourier-Mukai transform with kernel a Poincar&eacute; line bundle. We conjecture and hope to prove that the map from closed string fields to polyvector fields on $$\mathcal{H}\mspace{-1 mu}\mathit{iggs}$$ mentioned above is equivariant with respect to the actions of S- and T-duality, i.e. that the following diagram is commutative:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/closed-string-S-duality.png' | relative_url }}" alt="Relation between S- and T-duality" title="Relation between S- and T-duality"/>
    </div>
</div>
<br>

### Deformations of the categories of branes

The novel equivalences between categories of branes we wish to understand all arise as deformations of the equivalence proposed in the Dolbeault geometric Langlands conjecture. The way this equivalence, and consequently its deformations, arises in this setting is somewhat subtle. Namely, S-duality acts on the data of a *higher geometric quantisation* of the shifted cotangent bundle to $$\mathcal{H}\mspace{-1 mu}\mathit{iggs}$$.

This yields complications: until extremely recently higher geometric quantisation of shifted symplectic stacks was not a well understood topic, and was only defined for (shifted) cotangent bundles. This has now changed, with Safronov's recent preprint on shifted geometric quantizations {% cite Saf20 -f research-bib %}. The deformation theory of shifted geometric quantizations, and how deformations interact with automorphisms, is still an open question however.

Our investigations will shed light on what such a deformation theory would be comprised of. To this end, we are investigating a particular $$\mathbb{N}$$-indexed family of pairs of closed string fields related by S-duality, generalising the geometric Langlands conjecture (which is the case $$n=0$$). In the $$n=1$$ case we can conjecture that the category of modules for the Clifford algebra $$\text{Cl}_1$$ in vector bundles on $$C$$ is equivalent to a yet to be identified subcategory of modules for the Rees algebra of differential operators on $$\mathcal{H}\mspace{-1 mu}\mathit{iggs}$$. It is our hope that the work of Safronov may give us the tools required to specify the precise subcategory in question.

---

#### References:

{% bibliography -f research-bib --cited -T bib_proj %}
