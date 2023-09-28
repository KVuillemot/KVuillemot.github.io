---
layout: splash 
title:  "Research" 
permalink:  /research/ 
header:
  overlay_color: "#787878"
  overlay_filter: "0.5"
intro:
  - excerpt: "There you can find my talks, publications and scientific communications."
---

{% include feature_row id="intro" type="center" %}

# Publications

## 2023
### Preprint
* Michel Duprez, Vanessa Lleras, Alexei Lozinski, Killian Vuillemot. ϕ-FEM for the heat equation: optimal convergence on unfitted meshes in space. (accepted in CRAS)

  \[[preprint (hal)](https://hal.archives-ouvertes.fr/hal-03685445)], \[[codes (github)](https://github.com/KVuillemot/PhiFEM_Heat_Equation)]

## 2022
### Book chapter

* Stéphane Cotin, Michel Duprez, Vanessa Lleras, Alexei Lozinski, Killian Vuillemot. ϕ-FEM: an efficient simulation tool using simple meshes for problems in structure mechanics and heat transfer.
Partition of Unity Methods (Wiley Series in Computational Mechanics) 1st Edition, Wiley, 2022,
978-0470667088. hal-03372733

  \[[preprint (hal)](https://hal.archives-ouvertes.fr/hal-03372733)], \[[pdf (revue)](https://www.amazon.com/XFEM-Extended-Element-Computational-Mechanics/dp/0470667087)]

## 2021
### Lecture notes

* Franz Chouly, Xavier Dupuis, Killian Vuillemot. Analyse numérique MIGS 1re Année. Master.
France. 2021. hal-03277223

  \[[paper](https://cel.archives-ouvertes.fr/hal-03277223)]

# Talks 

- <details><summary>
September 2023: <i>A new unfitted finite element method: ϕ-FEM. </i>PhD students seminar, IMAG, Univ. Montpellier.</summary> <b> Abstract: </b>
ϕ-FEM is a new finite element method, proposed to solve partial differential equations on complex domains, using simple non conform meshes. The method relies on the use of a level-set function ϕ, which defines the domain and its boundary. In this presentation, I will introduce the method in the simple case of the resolution of the Poisson equation with Dirichlet boundary conditions. Then I will present the extension of the method to the case of time-dependent PDE's, and more precisely the case of the Heat equation with Dirichlet boundary conditions. Then, I will present a way to combine ϕ-FEM and neural networks. I will illustrate the efficiency of this method using numerical results.  </details>
\[[slides]({{ site.url }}/_data/beamer_montpellier.pdf)\]