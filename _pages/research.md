---
layout: splash 
title:  "Research" 
permalink:  /research/ 
header:
  overlay_color: "#ABCAF7"
  overlay_filter: "0.5"
intro:
  - excerpt: "There you can find my talks, publications and scientific communications."
---

<h1>{% include feature_row id="intro" type="center" %}</h1>
<hr style="border: 0;
        height: 3px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

# Publications

## 2023
### Scientific articles
* Michel Duprez, Vanessa Lleras, Alexei Lozinski, Killian Vuillemot. ϕ-FEM for the heat equation: optimal convergence on unfitted meshes in space. (accepted in CRAS)

  \[[preprint (hal)](https://hal.archives-ouvertes.fr/hal-03685445)], \[[paper](https://comptes-rendus.academie-sciences.fr/mathematique/item/10.5802/crmath.497.pdf)], \[[codes (github)](https://github.com/PhiFEM/Heat-Equation)]

<hr style="border: 0;
        height: 3px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

## 2022
### Book chapter

* Stéphane Cotin, Michel Duprez, Vanessa Lleras, Alexei Lozinski, Killian Vuillemot. ϕ-FEM: an efficient simulation tool using simple meshes for problems in structure mechanics and heat transfer.
Partition of Unity Methods (Wiley Series in Computational Mechanics) 1st Edition, Wiley, 2022,
978-0470667088. hal-03372733

  \[[preprint (hal)](https://hal.archives-ouvertes.fr/hal-03372733)], \[[pdf (revue)](https://www.amazon.com/XFEM-Extended-Element-Computational-Mechanics/dp/0470667087)], \[[codes (github)](https://github.com/PhiFEM/Poisson-Mixed-Boundary-Fracture-Interface)]

<hr style="border: 0;
        height: 3px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

## 2021
### Lecture notes

* Franz Chouly, Xavier Dupuis, Killian Vuillemot. Analyse numérique MIGS 1re Année. Master.
France. 2021. hal-03277223

  \[[paper](https://cel.archives-ouvertes.fr/hal-03277223)]

<hr style="border: 0;
        height: 5px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

# Talks 

- <details><summary>
September 2023: <i>A new unfitted finite element method: ϕ-FEM. </i>PhD students seminar, IMAG, Univ. Montpellier.</summary> <b> Abstract: </b>
ϕ-FEM is a new finite element method, proposed to solve partial differential equations on complex domains, using simple non conform meshes. The method relies on the use of a level-set function ϕ, which defines the domain and its boundary. In this presentation, I will introduce the method in the simple case of the resolution of the Poisson equation with Dirichlet boundary conditions. Then I will present the extension of the method to the case of time-dependent PDE's, and more precisely the case of the Heat equation with Dirichlet boundary conditions. Then, I will present a way to combine ϕ-FEM and neural networks. I will illustrate the efficiency of this method using numerical results.  </details>
\[[slides]({{ site.url }}/_data/beamer_montpellier.pdf)\]


- <details><summary>
February 2024: <i>Phi-FEM-FNO: a new approach to train a Neural Operator as a fast PDE solver for variable geometries. </i>MIMESIS/MLMS team seminar, Strasbourg.</summary> <b> Abstract: </b>
In this talk, we propose a way to solve partial differential equations (PDEs) by combining machine learning techniques and a new finite element method called phi-FEM. For that, we use the Fourier Neural Operator (FNO), a learning mapping operator. The purpose of this talk is to provide numerical evidence to show the effectiveness of this technique. We will focus here on the resolution of the Poisson equation with non-homogeneous Dirichlet boundary conditions. The key idea of our method is to address the challenging scenario of varying domains, where each problem is solved on a different geometry. Since we use the phi-FEM approach, we will consider domains defined by level-set functions. We will first recall the idea of phi-FEM and of the Fourier Neural Operator. Then, we will explain how to combine these two methods. We will finally illustrate the efficiency of this combination with some numerical results on two test cases.  </details>
<!-- \[[slides]({{ site.url }}/_data/beamer_montpellier.pdf)\] -->