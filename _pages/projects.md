---
layout: splash 
title:  "Projects" 
permalink:  /projects/ 
header:
  overlay_color: "#ABCAF7"
  overlay_filter: "0.5"
intro:
  - excerpt: "There you can find some of the projects I am (or was) working on."
classes: wide

LevelSet_tools:
  - image_path: ../_data/images/star_boundary.png
    alt: "from ls to boundary"
    excerpt: "Creation of boundary points from values of a level-set function."
  - image_path: ../_data/images/from_ls_to_mesh.png
    alt: "from ls to mesh"
    excerpt: "Creation of a triangular mesh from values of a level-set function."
---

<h1>
{% include feature_row id="intro" type="center" %}
</h1>
<hr style="border: 0;
        height: 3px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

## LevelSet tools : Python tools for domains defined by LS functions. 

The objective of this little project is to create a collection of small Python codes to interface between level-set functions and meshes. 
More precisely, the following can be easily, precisely, and rapidly done for 2D domains: 
  * creation of a set of boundary points from numpy arrays of values of LS function;
  * creation of conforming meshes from numpy arrays of values of LS function, that can be used with FEniCS;
The creation of 3D meshes is also available but is at this time not optimal because of the high computation time. 

  {% include feature_row id="LevelSet_tools" %}

The codes are available at :   \[[GitHub repository](https://github.com/KVuillemot/Project_M1_Parallelisation_en_temps)]


<hr style="border: 0;
        height: 3px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

## Internship (2021) : about the finite element method

First-year master's degree internship, under the supervision of Michel Duprez. This internship was an introduction to the standard finite element method and has for objective of discovering a new method called phi-FEM introduced by Michel Duprez, Vanessa Lleras, and Alexeï Lozinski in \[[paper](https://hal.archives-ouvertes.fr/hal-02521111)] and \[[paper](https://hal.archives-ouvertes.fr/hal-02521042v3)].

During this internship, we also introduced a new phi-FEM approach to solve Poisson problem with mixed boundary conditions, linear elasticity problems (Dirichlet conditions, Neumann conditions and mixed boundary conditions).

  \[[GitHub repository](https://github.com/KVuillemot/Stage_M1_Phi_FEM)]

<hr style="border: 0;
        height: 5px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">

## About the parareal in time algorithm

First year of Master's degree project. This project is a kind of introduction to ODEs resolution.
More precisely, we discuss here different schemes to solve these equations and the Parareal algorithm introduced by Jacques-Louis Lions, Yvon Maday, and Gabriel Turinici (in *Résolution d'EDP par un schéma en temps «pararéel »*).

  \[[GitHub repository](https://github.com/KVuillemot/Project_M1_Parallelisation_en_temps)]

<hr style="border: 0;
        height: 5px;
        background-image: linear-gradient(to right, rgba(0, 0, 0, 0), rgba(171,202,247), rgba(0, 0, 0, 0));">
        
## Bezier curves

Introduction to Bezier curves for a bachelor's degree project (in collaboration with Pauline Fossez and Estelle Laumont).

  \[[GitHub repository](https://github.com/KVuillemot/Projet_L3_Courbes_De_Bezier)]
