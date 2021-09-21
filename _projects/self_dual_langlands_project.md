---
layout: page
title: Self-dual geometric Langlands
description: A self-dual generalisation of geometric Langlands from Theory X
img: /assets/img/reductions-of-X-thumbnail.png
importance: 1
category: work
---

The mathematical study of the linearisation of symmetries, representation theory, has in modern times evinced deep ties to the physics of quantum field theories (QFTs). These ties are exemplified by the 2007 work of Anton Kapustin and Ed Witten on $$\mathcal{N}=4$$ 4d super Yang-Mills theory (SYM), a far reaching generalisation of electromagnetism. Kapustin and Witten realised that the *geometric Langlands program* -- the holy grail of modern geometric representation theory -- could be understood as the symmetry of SYM given by exchanging the electric and magnetic fields {% cite KapWit07 -f research-bib %}.

The goal of this project is to formulate and prove a self-dual version of the geometric Langlands program. The existence of self-dual Langlands is predicted by the symmetries of the QFTs of class $$\mathcal{S}$$ of Gaiotto, Moore and Neitzke {% cite GMN-WKB -f research-bib %}, which are themselves derived from a mysterious six-dimensional ur-theory known as "Theory $$\mathfrak{X}$$". Since its discovery, Theory $$\mathfrak{X}$$ has contributed widely both to mathematics (e.g. in knot theory {% cite Wit12 -f research-bib %}) and to physics (e.g. the influential AGT correspondence {% cite AGT10 -f research-bib %}).

A schematic overview of the derivation of usual and self-dual Langlands is presented in the diagram below. Roughly, higher dimensional theories give rise to lower dimensional theories through a process called "compactification" (the black arrows) and relative theories {% cite FT14 -f research-bib %} give rise to absolute theories through a process called "absolution" (the blue arrows).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/X.png' | relative_url }}" alt="Reductions of Theory X relevant to the usual and self-dual Langlands programs" title="Some reductions of theory X"/>
    </div>
</div>
<div class="caption">
    Reductions of Theory X relevant to the usual and self-dual Langlands program.
</div>

Certain symmetries of the higher dimensional theories are remembered by the lower dimensional theories. Following the right-hand path leads to SYM and the usual geometric Langlands duality, where the higher dimensional symmetry manifests as a symmetry *exchanging* two different 2d theories. Following the left-hand path leads to class $$\mathcal{S}$$ and the self-dual geometric Langlands duality, where the higher dimensional symmetry manifests as a symmetry of a *single* theory. See {% cite Der18a -f research-bib %} for details.

As part of this project, in {% cite Der18a Der20 -f research-bib %} I extended the results of {% cite HauTha03 DonPan12 -f research-bib %} to identify the SYZ mirror dual spaces for certain quotients of the moduli space of Higgs bundles, equipped with nontrivial B-fields. In examples where the input data for the moduli space is the same as the input data for a theory of class $$\mathcal{S}$$ I observe that the moduli space is *self dual*, and I conjecture that it is the 3d Coulomb branch of the corresponding theory of class $$\mathcal{S}$$. This is the content of the **self-dual Dolbeault Langlands correspondence**.

Future directions for this project include proving this conjecture, as well as extending to self-dual versions of the **de Rham** and **quantum** Langlands conjectures.

---

#### References:

{% bibliography -f research-bib --cited -T bib_proj %}
