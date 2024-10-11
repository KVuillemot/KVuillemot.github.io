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

## Scientific articles
### 2024 
*  **φ-FD : A well-conditioned finite difference method inspired by ϕ-FEM for general geometries on elliptic PDEs.** M. Duprez, V. Lleras, A. Lozinski, V. Vigon and K. Vuillemot. (submitted)

   \[[preprint(hal)](https://hal.science/hal-04731164)], \[[codes (github)](https://github.com/PhiFEM/PhiFD)]


*  **φ-FEM-FNO: a new approach to train a Neural Operator as a fast PDE solver for variable geometries.** M. Duprez, V. Lleras, A. Lozinski, V. Vigon and K. Vuillemot. (submitted)

   \[[preprint(hal)](https://hal.science/hal-04473794)], \[[codes (github)](https://github.com/KVuillemot/PhiFEM_and_FNO/tree/main)]


### 2023
* **φ-FEM for the heat equation: optimal convergence on unfitted meshes in space.** Michel Duprez, Vanessa Lleras, Alexei Lozinski, Killian Vuillemot. (accepted in CRAS)

  \[[preprint (hal)](https://hal.archives-ouvertes.fr/hal-03685445)], \[[paper](https://comptes-rendus.academie-sciences.fr/mathematique/item/10.5802/crmath.497.pdf)], \[[codes (github)](https://github.com/PhiFEM/Heat-Equation)]

<hr style="border: 0;
        height: 3px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

## Book chapter

*  **φ-FEM: an efficient simulation tool using simple meshes for problems in structure mechanics and heat transfer.** Stéphane Cotin, Michel Duprez, Vanessa Lleras, Alexei Lozinski, Killian Vuillemot. 
*Partition of Unity Methods (Wiley Series in Computational Mechanics)*, 2022.
  \[[preprint (hal)](https://hal.archives-ouvertes.fr/hal-03372733)], \[[pdf (revue)](https://www.amazon.com/XFEM-Extended-Element-Computational-Mechanics/dp/0470667087)], \[[codes (github)](https://github.com/PhiFEM/Poisson-Mixed-Boundary-Fracture-Interface)]

<hr style="border: 0;
        height: 3px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

## Lecture notes

* **Analyse numérique MIGS 1re Année. Master.** Franz Chouly, Xavier Dupuis, Killian Vuillemot. France. 2021  \[[Cours (hal)](https://cel.archives-ouvertes.fr/hal-03277223)]

<hr style="border: 0;
        height: 5px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

# Talks 

- <details><summary>
September 2023: <i>A new unfitted finite element method: φ-FEM. </i>PhD students seminar, IMAG, Univ. Montpellier.</summary> <b> Abstract: </b>
φ-FEM is a new finite element method, proposed to solve partial differential equations on complex domains, using simple non conform meshes. The method relies on the use of a level-set function φ, which defines the domain and its boundary. In this presentation, I will introduce the method in the simple case of the resolution of the Poisson equation with Dirichlet boundary conditions. Then I will present the extension of the method to the case of time-dependent PDE's, and more precisely the case of the Heat equation with Dirichlet boundary conditions. Then, I will present a way to combine φ-FEM and neural networks. I will illustrate the efficiency of this method using numerical results.  </details>
\[[slides]({{ site.url }}/_data/beamer_montpellier.pdf)\]


- <details><summary>
February 2024: <i>φ-FEM-FNO: a new approach to train a Neural Operator as a fast PDE solver for variable geometries. </i>MIMESIS/MLMS team seminar, Strasbourg.</summary> <b> Abstract: </b>
In this talk, we propose a way to solve partial differential equations (PDEs) by combining machine learning techniques and a new finite element method called φ-FEM. For that, we use the Fourier Neural Operator (FNO), a learning mapping operator. The purpose of this talk is to provide numerical evidence to show the effectiveness of this technique. We will focus here on the resolution of the Poisson equation with non-homogeneous Dirichlet boundary conditions. The key idea of our method is to address the challenging scenario of varying domains, where each problem is solved on a different geometry. Since we use the φ-FEM approach, we will consider domains defined by level-set functions. We will first recall the idea of φ-FEM and of the Fourier Neural Operator. Then, we will explain how to combine these two methods. We will finally illustrate the efficiency of this combination with some numerical results on two test cases.  </details>
<!-- \[[slides]({{ site.url }}/_data/beamer_montpellier.pdf)\] -->

- <details><summary>
April 2024: <i>A new unfitted finite element method: φ-FEM. </i>PhD students seminar, IRMA, Univ. Strasbourg.</summary> <b> Abstract: </b>
φ-FEM is a new finite element method, proposed to solve partial differential equations on complex domains, using simple non conform meshes. The method relies on the use of a level-set function φ, which defines the domain and its boundary. In this presentation, I will introduce the method in the simple case of the resolution of the Poisson equation with Dirichlet boundary conditions. Then I will present the extension of the method to the case of time-dependent PDE's, and more precisely the case of the Heat equation with Dirichlet boundary conditions. Then, I will present a way to combine φ-FEM and neural networks. This method, called φ-FEM-FNO, has been introduced to achieve the resolution of multiple physics problems with good accuracy in real time. I will illustrate the interest of this approach with numerical results on two test cases solving the Poisson-Dirichlet equation on different types of shapes.  </details>

- May 2024: <i>φ-FEM-FNO: a new approach to train a Neural Operator as a fast PDE solver for variable geometries. </i>[CANUM](https://canum2024.math.cnrs.fr/fr/), Ile de Ré.
  \[[slides]({{ site.url }}/_data/canum.pdf)\]

- <details><summary>
June 2024: <i>A φ-FEM approach to train a FNO for variable geometries. </i>[ECCOMAS](https://eccomas2024.org), Lisbon.</summary> <b> Abstract: </b>
φ-FEM is a new finite element method, proposed to solve partial differential equations on complex domains, using non-conforming meshes. The method relies on the use of a level-set function φ, which defines the domain and its boundary. In this presentation, we propose a way to combine this method and machine learning techniques (here the Fourier Neural Operator). This method, called φ-FEM-FNO, has been introduced to achieve the resolution of multiple physics problems with good accuracy in real time. For that, the neural operator is trained using synthetic φ-FEM data and the functions defining the governing equations to solve. The preliminary numerical results are very encouraging since for two test cases solving the Poisson-Dirichlet equation on different types of shapes, our approach reaches the precision of a standard finite element method, 100 times faster. </details>
\[[slides]({{ site.url }}/_data/eccomas.pdf)\]
