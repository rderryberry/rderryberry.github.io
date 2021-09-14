---
layout: page
title: Integrable harmonic map equations
description: Constructing integrable harmonic map equations from 4d Chern-Simons
img: /assets/img/marked-torus.png
importance: 2
category: work
---

As part of their work on deriving integrable systems from 4d Chern-Simons theory, Costello and Yamazaki {% cite CY2019 -f research-bib %} give a physical construction of a class of two-dimensional classical integrable field theories from the data of an algebraic curve $$C$$,  a one-form $$\omega$$ on $$C$$, and a reductive group $$G$$.  Fixing the input data, the target space of this integrable field theory is a certain open substack of $$\text{Bun}_G(C)$$ which I will denote $$\text{Bun}_G^0(C)$$. The existence of this integrable field theory implies a number of remarkable and novel algebro-geometric structures on $$\text{Bun}_G^0(C)$$.

In the paper {% cite Der21 -f research-bib %} I gave an algebro-geometric construction of these expected geometric structures, and proved that they satisfied the properties expected from the work of Costello and Yamazaki.

Specifically, the structures that I construct on $$\text{Bun}_G^0(C)$$ are, firstly, an algebraic metric and an algebraic 3-form. These are what are needed to define a classical $$\sigma$$-model with target $$\text{Bun}_G^0(C)$$.  Further, for each $$z \in C$$, I find *two* algebraic connections on the evaluation bundle $$P_z$$ over $$\text{Bun}_G^0(C)$$.  From the $$\sigma$$-model perspective, these two connections are what is needed to define the Lax matrix for a specific harmonic map equation (the equations of motion for the $$\sigma$$-model). The primary result of this paper is therefore that the class of harmonic map equations which arise in this manner are all integrable.

Future directions for this project include:
- The construction of explicit solutions to the harmonic map equations.
- Leveraging integrability to understand the topology of the space of harmonic maps (cf {% cite Uhl89 -f research-bib %}).
- Proving a conjecture of Costello on the form of the 1-loop beta function for the $$\sigma$$-model (the statement and partial results can be found in {% cite Der21 -f research-bib %}).

---

#### References:

{% bibliography -f research-bib --cited -T bib_proj %}
